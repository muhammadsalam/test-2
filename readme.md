-   Задача

первая страница
слайдер (https://itchief.ru/javascript/slider)
1000px - 3
800px- 2
640px - 1

в одном слайде блоки:

-   изображение
-   title
-   автор и время
-   small-description
-   кнопка "подробнее"

при клике на слайд переход на страницу 2 + докрутка до выбранного блока

Страница 2
горизонтальные блоки

-   слева изображение
-   справа текстовый блок
    -- слева title, справа автор и время
    -- description

при 640px

-   сверху изображение
-   снизу текстовый блок
    -- title
    -- автор и время
    -- description

у слайдера и горизонтального блока:
brder: 1px solid #9f9f9f;
border-radius: 7px;

общий главный wrapper
max-width: 12000px
padding: 29px
box-sizing: border-box
возле времени svg иконка часов

желательно без файлов css и js
то есть, только html и папка images
и два файла сладера

<link href="./itc-slider/itc-slider.min.css" rel="stylesheet">
<script src="./itc-slider/itc-slider.min.js"></script>

реализацию слайдера можно посмотреть/скопировать на https://topaddress.ae
