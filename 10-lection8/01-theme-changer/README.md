# Переключатель темы

В скрипте `theme-changer.js` описана следующая логика работы - при переключении чекбокса с id=`theme-changer` выставляется атрибут `data-theme-dark` на элемент `html`. Если атрибут `data-theme-dark` уже есть на элементе `html`, то атрибут удаляется.

1. Чекбоксу переключения темы нужно присвоить id `theme-changer`.
2. По атрибуту на html написать селектор и переопределить цвета страницы.

Цвета нужно брать с уже готового проекта - [https://course-htmlcss.javascript.ru/](https://course-htmlcss.javascript.ru/)
