# scoop-yt

[Scoop](https://scoop.sh/) bucket для [yt — Yandex Tracker CLI](https://github.com/RoboNET/YandexTrackerCLI).

## Установка

```powershell
scoop bucket add yt https://github.com/RoboNET/scoop-yt
scoop install yt
```

## Обновление

```powershell
scoop update yt
```

## Как обновляется bucket

`yt.json` обновляется автоматически из workflow [`update-scoop-bucket.yml`](https://github.com/RoboNET/YandexTrackerCLI/blob/main/.github/workflows/update-scoop-bucket.yml) основного репозитория при публикации каждого нового релиза. Manifest содержит блок `autoupdate`, поэтому Scoop умеет тянуть новые версии и без обновления самого manifest'а.

## Лицензия

MIT — см. [yt CLI license](https://github.com/RoboNET/YandexTrackerCLI/blob/main/LICENSE).
