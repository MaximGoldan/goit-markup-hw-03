# HM-1-desktop

/_ селекторы _
/_ универсальный _
тега - p
кнопки и teg adress не унаследуют шрифт надо вручную
id используетс ядля ссылки в тесте при нажатии перекинут на то место где это необходимо ЕГО не используем - # text

клас (. css) (class - html) самі популярній но проблема вибирать название класса
h1,h2,h3 - title
p - text
nav - navigatia
list- список ul
item - єлемент списка li
link - ссылка
атрибут
[href] все ссілки відялятся в той цвет которій зададим
[href] {
color: aqua; }
дочерний .team > p {
color: rgb(172, 239, 16); }
потомка
.team p {
color: rgb(172, 239, 16); }
\*/
/_ задал цвет рамки.header-item {
outline: 1px solid red;
} _/

/_ крайняя геометрия.
Всем едлементом с класом item которіе находятся внутри header-list
не являются последними детьми в своей коллекции_/

/_ .header-list .header-item:not(:last-child) {
margin-right: 50px;
} _/
.portfolio-list {
display: flex;
flex-wrap: wrap;
/_ justify-content: space-between; _/
gap: 10px;
padding: 0;
list-style: none;
background-color: yellowgreen;
}

.portfolio-item {
/_ width: calc((100% - 60px) / 3); _/
margin-right: 30px;
margin-bottom: 30px;
}
.portfolio-item:nth-child(3n) {
margin-right: 0;
}

.portfolio-item:nth-last-child(-n + 3) {
margin-bottom: 95px;
}
