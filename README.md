# MetroStroy Loading Screen

Кастомный loading screen для Garry's Mod / Metrostroi.

## Структура
- `index.html` — загрузочный экран
- `assets/background.jpg` — фон
- `assets/background_alt.jpg` — дополнительный фон
- `assets/discord_qr.jpg` — QR-код Discord
- `server.cfg.example` — пример `sv_loadingurl`

## GitHub Pages
1. Создайте публичный репозиторий.
2. Загрузите `index.html` и папку `assets`.
3. В Settings → Pages включите публикацию из ветки `main`, папка `/root`.
4. Полученный адрес укажите в `sv_loadingurl`.

Пример:
`sv_loadingurl "https://ВАШ-ЛОГИН.github.io/ВАШ-РЕПОЗИТОРИЙ/"`

Garry's Mod передаёт странице данные через `GameDetails`, а статус загрузки — через `SetStatusChanged` и `DownloadingFile`.
