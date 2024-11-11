# HTML For EPC Hunters

## Демо


## Описание
Верстка страницы по макету Figma

### Структура проекта
В папке src/scss содержатся файлы стилей:
- common - общая компоновка элементов, общие блоки (кнопка, заголовки)
- steps - основная секция
- header - шапка и ее элементы
- fonts - шрифты
- vars - переменные
- style - основной файл для подключения модулей

В папке src/img/icons содержатся файлы svg для преобразования в спрайт

### Стек
- html
- js
- SCSS
- gulp
- git
- swiper

Все взаимодействия с DOM-элементами (кроме слайдера) написаны на javascript без дополнительных библиотек и плагинов

## Функционал сборки
- компиляция препроцессора SCSS
- минификация CSS
- автоматическое добавление префиксов CSS
- преобразования кода ECMAScript 2015 + в обратно совместимую версию JavaScript с помощью Babel
- минификация js
- создание svg-sprite
- отслеживание изменений в файлах и автоматический запуск повторной обработки
- генерация sourcemaps
- локальный сервер с автоматическим обновлением страницы при изменении файлов

## Запуск:  
Установите глобально пакет gulp-cli

``
npm i gulp-cli
``
1. Скачать все файлы проекта  
2. В терминале перейти в каталог проекта  
3. Выполнить команду: npm i  
4. Выполнить команду: gulp (запуск таска default)