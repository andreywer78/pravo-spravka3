# ПравоСправка v2

Готовая статическая версия для GitHub Pages.

## Публикация

1. Создайте GitHub repository.
2. Загрузите **содержимое этой папки**, а не саму папку целиком.
3. В корне репозитория должны лежать `index.html`, `style.css`, `app.js`, `config.js`.
4. Откройте **Settings → Pages**.
5. В **Build and deployment** выберите **Deploy from a branch**.
6. Branch: `main`, Folder: `/ (root)`.
7. Сохраните настройки и дождитесь завершения GitHub Actions/деплоя.

Если репозиторий называется `pravo-spravka2`, адрес сайта будет вида:
`https://ВАШ-ЛОГИН.github.io/pravo-spravka2/`

Не открывайте `https://ВАШ-ЛОГИН.github.io/`, если это project repository.

## Supabase

Перед работой с регистрацией и базой выполните `supabase.sql` в SQL Editor проекта Supabase. В `config.js` должны быть Project URL и Publishable/anon key. `service_role` key в браузерный код помещать нельзя.
