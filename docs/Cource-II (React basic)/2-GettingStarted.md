## React

**[React](https://react.dev)** — это JavaScript-библиотека для разработки пользовательского интерфейса. Он не умеет ничго кроме создания компонент. Для http запросов, роутинга, глобальныго состояния используются сторонние библиотеки. Поэтому официальная документация советует использовать фреймоворки ([Next](https://nextjs.org), [Remix](https://remix.run)) вместо классических React приложений ([CRA](https://create-react-app.dev)). Но в реальности вы больше будете работать с последним.

Фреймворки позволяют использовать сложные архитектуры и дают готовый набор инструментов реализации. Но главное фреймворки позволяют очень легко создавать приложения отлично оптимизированные по скорости загрузки и [SEO](https://ru.wikipedia.org/wiki/Поисковая_оптимизация). Однако большенству приложений скорость загрузки и SEO излишни.

## Как создать приложение

[CRA](https://create-react-app.dev) – инструмент создающий, одной коммандой, минимальное React приложение.

[Создаем приложение](https://create-react-app.dev/docs/getting-started#creating-an-app) такой командой `pnpm create react-app my-app` (если CLI предложит использовать TypeScript или добавить тесты то отказываемся).

Когда команда пробежит откройте директорию приложения `my-app` в VScode. Вы увидете примерно такую структуру проекта:

```
my-app
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    ├── serviceWorker.js
    └── setupTests.js
```

Далее запустите команду `pnpm start`.
Вот и первое приложение)

## Сруктура приложения

*README.md* – просто файлик для документирования проекта, не является частью проекта.
*[node_modules](https://medium.com/@snehalv.2010/what-is-node-modules-folder-f13b5c32dd8b)* – папка в которую сохраняются зависимости приложения.

Идем дальше – [крестики нолики](https://github.com/Osipchik/FrontendGang/blob/master/docs/Cource-II%20(React%20basic)/3-TicTakToe.md).

