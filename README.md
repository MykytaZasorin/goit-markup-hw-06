📘 Модуль 4.1: Декоративні елементи

🎨 Властивості: background-color, background-image, background-repeat, background-position, background-size

🌈 Градієнти: лінійний, радіальний
🕶 CSS-тіні та властивість box-shadow

🧙‍♀️ Псевдоелементи ::before та ::after

🔁 background-repeat
repeat — повторювати X і Y. Значення за замовчуванням.
repeat-x — повторювати тільки X (горизонтально).
repeat-y — повторювати тільки Y (вертикально).
no-repeat — не повторювати.
📍 background-position
x y
50% 50%
100px 200px
right bottom
left top
📏 background-size
auto auto
200px
200px 300px
cover — масштабувати, щоб покрити весь елемент
contain — масштабувати, щоб вмістити зображення всередину елемента

background-image: url(шлях до зображення 1), url(шлях до зображення 2);

🔄 Лінійний градієнт
Синтаксис:
background-image: linear-gradient(<напрямок>, <колір-1>, <колір-2>, ...)

Приклад з фоном:
background-image: linear-gradient(to top, rgba(17, 17, 17, 0.4), rgba(17, 17, 17, 0.4)), url("path_to_image");

🎯 Радіальний градієнт
Приклад:
background-image: radial-gradient(rgba(17, 17, 17, 0.3), rgba(17, 17, 17, 1)), url("path_to_image");

🧰 background (скорочена форма)
Приклад:
background: url(шлях до зображення) repeat-x;

🕶 Властивість box-shadow
Синтаксис:
box-shadow: <x-offset> <y-offset> <blur> <spread> <color>;

Можна додати inset для внутрішньої тіні:
box-shadow: inset <x-offset> <y-offset> <blur> <spread> <color>;

🔳 Багатошарова тінь
Приклад:
box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1), 0px 6px 20px rgba(0, 0, 0, 0.1);

🔗 Приклади: getcssscan.com/css-box-shadow-examples

📐 Векторна графіка
Вбудований SVG (inline)
Властивість fill — визначає колір заливки
Властивість stroke — визначає колір рамок
🧰 SVG-спрайт
Генерація через: icomoon.io/app

Оптимізація SVG: svgomg.net

<svg class="class-name" width="24" height="24"> <use href="./sprite.svg#icon-instagram"></use> </svg>

🧙‍♀️ Псевдоелементи
Використання:
.box::before, .box::after, .box:hover::before
