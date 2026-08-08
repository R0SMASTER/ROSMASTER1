# РосМастер — полный сайт для rosmaster.moscow

Готовая статическая версия сайта для GitHub Pages.

## Что изменено для нового домена

- Все SEO-ссылки `rosmaster.pro` заменены на `rosmaster.moscow`.
- Обновлены canonical, Open Graph, Schema.org, robots.txt и sitemap.xml.
- `CNAME` содержит `rosmaster.moscow`.
- Старый Vercel-обработчик заявок и конфигурация Vercel удалены: GitHub Pages не выполняет серверный код.
- Две формы на главной странице теперь открывают WhatsApp с сформированной заявкой, поэтому работают на GitHub Pages без токенов и сервера.
- Удалены устаревшие скрипты Cloudflare Challenge, которые не нужны на GitHub Pages.

## Публикация

1. Загрузите содержимое этой папки в корень репозитория GitHub `ROSMASTER1`, заменив одноимённые файлы.
2. В GitHub: `Settings → Pages → Custom domain` укажите `rosmaster.moscow`.
3. В DNS настройте четыре A-записи GitHub Pages для `@` и CNAME `www → r0smaster.github.io`.
4. После выпуска сертификата включите `Enforce HTTPS`.

## Контакты

Номер WhatsApp в файле `index.html`: `79015056088`. При необходимости замените номер во всех ссылках `wa.me`.

## Безопасность

Не добавляйте токены Telegram-ботов, API-ключи или пароли в публичный репозиторий.
