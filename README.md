# photostudio-cabinet

Браузерный кабинет платформы фотостудий (Фаза 2). Статика на GitHub Pages,
custom domain `app.poont.space`. Бэкенд — общий:
`https://photostudio-backend-yehh.onrender.com`.

- `cabinet.html` — вход владельца/админа студии через Telegram Login Widget,
  список своих студий, управление (пока скелет).
- `platform.html` — кабинет платформы (позже).

Вход работает только когда страница открыта с домена, привязанного к боту
`@poontstudio_bot` через `@BotFather /setdomain`, и когда на Render задан
`PLATFORM_BOT_TOKEN`.
