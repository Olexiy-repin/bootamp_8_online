# Подключение локальных шрифтов

## 1. Найти и скачать нужный шрифт

---

- зайти на [google-webfonts-helper](https://google-webfonts-helper.herokuapp.com/fonts)
- найти нужный шрифт
- выбрать интересующий язык и жирность шрифта <img src="./images/img-1.png" alt="выбор языка и жирности шрифта" width="640" height="auto">
- переключиться на Modern Browsers, что бы шрифт скачивался в двух форматах woff и woff2. Скачать шрифт. <img src="./images/img-2.png" alt="выбор форматов для современных браузеров и скачивание шрифта" width="640" height="auto">
- распаковываем архив и переносим всё содержимое к нам в проект, в папку fonts <img src="./images/img-3.png" alt="шрифты в папке fonts" width="640" height="auto">

## 2. Подключение шрифта

---

- Скопировать директивы `@font-face`, которые предлагал google-webfonts-helper <img src="./images/img-4.png" alt="копирование директив @font-face" width="640" height="auto">
- Вставить эти диркетивы вверху наших стилей, если есть `:root`, то после него <img src="./images/img-5.png" alt="вставка директив @font-face" width="640" height="auto">
- Внутри директивы `@font-face`, идёт описание шрифта, если копировали с google-webfonts-helper, то ничего там менять не надо.

## 3. Проверяем работоспособность шрифта

---

- <img src="./images/img-6.png" alt="вешаем на title и text шрифт" width="640" height="auto">
- <img src="./images/img-7.png" alt="проверяем подключился ли шрифт на title" width="640" height="auto">
- <img src="./images/img-8.png" alt="проверяем подключился ли шрифт на text" width="640" height="auto">
