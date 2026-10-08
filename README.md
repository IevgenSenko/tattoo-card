# Сайт-визитка тату-мастера

Статическая страница на русском без сборки, JavaScript и внешних зависимостей.

## Посмотреть и изменить

Откройте `index.html` двойным щелчком в браузере. Тексты, имя и контакты редактируются в `index.html`, цвета и оформление — в `style.css`. Все данные сейчас являются заглушками.

Для фотографий создайте папку `images` рядом с `index.html`. Положите туда свои изображения, например `work-1.jpg`. Замените соответствующий блок `<div class="photo …">…</div>` на:

```html
<img class="photo" src="images/work-1.jpg" alt="Краткое описание вашей татуировки">
```

Заглушки контактов сейчас не кликабельны. Для Telegram замените текст контакта на `<a href="https://t.me/ВАШ_USERNAME">@ВАШ_USERNAME</a>`, для почты — на `<a href="mailto:ВАША_ПОЧТА">ВАША_ПОЧТА</a>`. Используйте только свои настоящие данные. Замените также название в `<title>` и описание страницы в `<meta name="description">`.

## Загрузить на GitHub

1. Войдите в GitHub и создайте новый публичный репозиторий. Можно назвать его `tattoo-card`.
2. На странице пустого репозитория выберите **uploading an existing file**. В существующем репозитории — **Add file → Upload files**.
3. Перетащите содержимое этой папки: `index.html`, `style.css`, `README.md`, а позднее и папку `images`. Файл `index.html` должен находиться в корне репозитория, а не внутри папки `tattoo-card`. ZIP загружать не нужно.
4. Нажмите **Commit changes**.
5. Откройте **Settings → Pages**. В разделе **Build and deployment** выберите **Deploy from a branch**, ветку **main** и папку **/(root)**. Нажмите **Save**.
6. Дождитесь публикации. Адрес появится в **Settings → Pages**; обычно он имеет вид `https://ВАШ_ЛОГИН.github.io/tattoo-card/`.

Для дальнейших правок открывайте нужный файл в GitHub, нажимайте значок карандаша и сохраняйте через **Commit changes**. GitHub Pages обновит страницу после завершения публикации.

Официальные инструкции: [загрузка файлов](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository), [настройка GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
