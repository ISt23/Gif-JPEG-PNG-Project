<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="utf-8" />
</head>
<body>
<img src="priroda_gory_nebo_ozero_oblaka_81150_1920x1080.jpg">
<img src="background-2390367_960_720.png">
<img src="c97fe4d68fbaa154f8d7f4fa596b2474.gif">
<!--Создаём таблицу контейнер, которой задаём следующее
оформление:
border="1"
align="center"
rules="rows"
style="width:60%;" 
<table
border="1"
align="center"
rules="rows"
style="width:60%;">
<!--Создаём строку-->
<tr>
<!--Создаём ячейку строки-->
<td>
<!--ШАПКА САЙТА-->

<!--В ячейке строки создаём ещё одну таблицу для шапки сайта.
Оформление:
border="1" - двойная рамка толщиной в 1px
background="images/168.png" - картинка в шапке сайта, если требуется.
Адрес картинки вы должны вставить свой.
bgcolor="#7FFFD4" - фоновый цвет в шапке, если нет картинки.
cellpadding="10" - отступ содержимого от рамки не менее 10px.
style="width:100%; border-radius:5px;" - добавляем "резиновость"
и закругляем уголки рамки-->
<table
border="1"
background="images/168.png"
bgcolor="#7FFFD4"
cellpadding="10"
style="width:100%; border-radius:5px;">
<!--Создаём строку таблицы-->
<tr>
<!--Создаём столбец таблицы-->
<th>
<!--Содержание ячейки столбца-->
<h1>Gif-JPEG-PNG-Project</h1>
<!--Закрываем таблицу-->
</th>
</tr>
</table>

<!--ОСНОВНОЙ КОНТЕНТ-->

<!--В этой же ячейке контейнера создаём ещё одну таблицу
для основного контента.
Оформление как и в предыдущей таблице-->

<table
border="1"
bgcolor="#e6e6fa"
cellpadding="10"
style="width:100%; border-radius:5px;">
<!--Создаём строку-->
<tr>
<!--Создаём ячейку
Оформление:
rowspan="2" - объединяем две ячейки в одну.
Число объединяемых ячеек по числу ячеек в сайдбаре.
style="width:80%" - основной контент занимает 80% всей площади,
оставшиеся 20% для сайдбара-->
<td
rowspan="2"
style="width:80%">
<h2>Страница</h2>
<!--Начинаем абзац с красной строки-->
<p style="text-indent:20px">


<!--САЙДБАР-->

<!--Создаём ячейку сайдбара-->
<td bgcolor="#e6e6fa">
<h3>Ссылки</h3>
<!--Абзац для ссылки на страницу сайта-->
<p>
<!--Ссылка на страницу сайта-->
<a href="">
<!--Картинка маркера перед названием страницы-->
https://imgur.com/a/hRt53t3
<!--Название страницы
style="margin-left:5px;" - отступ названия от маркера-->
<span style="margin-left:5px;">JPG</span></a>
<!--Закрываем абзац-->
</p>
<p>
<a href="">
https://ibb.co/zR4f711
<span style="margin-left:5px;">PNG</span;></a>
</p>
<p>
<a href="">
https://ibb.co/BNZ3FDf
<span style="margin-left:5px;">GIF</span></a>
</p>
</td>
</tr>
</table>
</body>
</html>
