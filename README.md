# Ловец номеров

- `server/` — сервер (Node.js, Docker). Нужен хостинг; пароль ADMIN задаётся переменной окружения `ADMIN_PASSWORD`.
- `app/` — оболочка Android. Перед сборкой впиши адрес сервера в `app/www/config.js`.
- `.github/workflows/apk.yml` — сборка APK на GitHub (вкладка Actions → Build APK → Run workflow → скачать `lovec-apk`).
