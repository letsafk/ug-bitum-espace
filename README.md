# GitHub Pages + Tilda

## 1. Что загружать в GitHub

Загрузите содержимое папки `github-pages-embed` в репозиторий GitHub.

Внутри нужны файлы:
- `index.html`
- `tilda-embed.css`
- `tilda-embed.js`
- папка `assets/`

## 2. Как включить GitHub Pages

1. Откройте репозиторий на GitHub.
2. Зайдите в `Settings` -> `Pages`.
3. В `Build and deployment` выберите `Deploy from a branch`.
4. Выберите branch `main` и папку `/root` или `/docs`, смотря куда вы загрузили файлы.
5. Сохраните и дождитесь публикации сайта.

GitHub Pages публикует обычные статические файлы из репозитория. По официальной документации сайт может обновиться не мгновенно и публикация иногда занимает до 10 минут.

## 3. Что вставлять в Tilda

В HTML-элемент Zero Block или в T123 вставьте код из файла `tilda-snippet-template.html`.

Перед вставкой замените:
- `YOUR-USERNAME` на ваш логин GitHub
- `YOUR-REPO` на имя репозитория

Пример:
`https://vasya123.github.io/ug-bitum/tilda-embed.js`

## 4. Формы Tilda

Кнопки в лендинге уже открывают ссылки:
- `#popup:ugbitumcallback`
- `#popup:ugbitumcost`

Поэтому на странице Tilda нужно добавить две стандартные pop-up формы и настроить их по файлу `../tilda-forms-setup.md`.

## 5. Что делать после загрузки

1. Сначала откройте GitHub Pages URL и проверьте, что лендинг открывается сам по себе.
2. Потом вставьте snippet в Tilda.
3. Потом добавьте две Tilda pop-up формы.
4. Потом сделайте тестовую заявку.
