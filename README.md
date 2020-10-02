## Установка

1. Вызывать yarn / npm i
2. (Желательно) Вызывать yarn proxy / npm run proxy, для конфигурации проксей шарика. Если пропустить этот шаг, live сервер все равно запуститься.

## Доступные скрипты

В директории проекта вы можете запускать:

### `yarn proxy`

Необходимо запустить один раз для конфигурации прокси для live сервера.

### `gulp add --page YourPageName`

Создает мини приложение в папке src/your-page-name-app, где хранятся исходиники вашей будущей страницы YourPageName<br />

### `yarn build-your-page-name-app`

Собирает ваш апп и кладёт файлы и кладёт в папку ./build/SiteAssets/Pages/YourPageName<br />

### `yarn build`

Запускает build-\*-app для всех созданных вами страниц <br />

### `yarn start-your-page-name-app`

Запускает live сервер разработчика с вашим аппом на уникальном порту<br />
