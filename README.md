# Удобный шаблон для разработки фронтенд приложний 

#### Легко интегрируется с различными сборщиками (Vite, Webpack)

#### Тут уже используются некоторые пакеты для vue.js, рекомендую использовать Vue + Vite

Установка:
1. npm i
2. npm run prepare (для связывания husky с git)
3. Работать

Для автоматического исправления ошибок и форматирования при сохранении файла в vscode, нужно:
1. Перейти в настройки ctrl + shift + p
2. Open User Settings (JSON)
3. Добавить следующий код:
```
"editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit",
    "source.fixAll.stylelint": "explicit"
  },
```

> Также при работе с Vue, форматтер по умолчанию должен быть выключен (default formatter: none)
Это нужно для правильного форматирования шаблона, стилей и js/ts внутри .vue файлов
