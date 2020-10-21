# Тестовое задание на позицию frontend-разработчик

Сверстать адаптивную страницу с формой и выводом полученных по API NASA 25 изображений с камеры марсохода в выбранный земной день. Выбрать удачные первоначальные настройки марсохода/камеры/дня по своему усмотрению. Фоновое изображение должно меняться в соответствии с выбранным земным днем. По клику на кнопку Искать должно происходить обновление изображений в соответствии с выбранными параметрами. Изображения должны выводится в случайном порядке из всего массива полученных данных. 

Верстку осуществить в соответствии с макетом созданным в Фигме для 3 breakpoints: 375px, 768px, 1280px.


### Поля формы

1. Марсоход
2. Камера марсохода
3. Земной день
4. Кнопка Искать

## Используемые технологии

Можно использовать один из JS фреймворков: Vue.js, React, AngularJS

Для стилей использовать SCSS, Sass или Less. Для генерации CSS - gulp, webpack и т.п.

В верстке и стилях использовать методологию БЭМ или другую. Выбор обосновать.

Для адаптивной верстки нужно использовать media queries, Нельзя использовать HTML/CSS фреймворки.

Для всего остального HTML/CSS/JS фреймворки использовать можно. Выбор фреймворка необходимо обосновать.


## Результат

Результатом задания должен быть проект в репозитории GitHub с инструкцией для развертывания на *nix/Os системах в файле readme.
Проект должен содержать HTML страницу открыв которую в браузере можно проверить работу формы и получение данных по API.
Ссылку на репозиторий с выполненным заданием отправить на support-web@technoavia.ru

## Данные
Использовать API Nasa: 

### Mars Rover Photos 

Для получения фотографий в соответствии с параметрами: марсоход, камера марсохода, выбранный земной день

### APOD

Для получения фоновой картинки по выбранному в форме земному дню

## Ссылки

### API Nasa

https://api.nasa.gov/

### Фигма

https://www.figma.com/file/Op7k07bCr8RS6ERlEkeaKM/frontend-dev?node-id=0%3A1
