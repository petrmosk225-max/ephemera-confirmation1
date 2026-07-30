# Статичная страница подтверждения Ephemera

Эта папка готова для публикации через GitHub Pages.

Внутри нет JavaScript: браузер загружает обычный `index.html` и `style.css`.

## Как опубликовать через GitHub Pages

1. На GitHub создай новый репозиторий, например `ephemera-confirmation`.
2. Сделай репозиторий публичным.
3. Загрузи в корень репозитория файлы `index.html` и `style.css`.
4. Открой в репозитории **Settings → Pages**.
5. В разделе **Build and deployment** выбери:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main`
   - папка: `/ (root)`
6. Нажми **Save** и подожди 1–3 минуты.

GitHub покажет публичный адрес примерно такого вида:

`https://ТВОЙ-ЛОГИН.github.io/ephemera-confirmation/`

После получения адреса его нужно будет добавить в Supabase в **Authentication → URL Configuration**, а затем заменить redirect URL в приложении.
