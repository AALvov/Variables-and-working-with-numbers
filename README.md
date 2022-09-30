# Variables-and-working-with-numbers
JS базоый- практическая работа 2

Задача 1

Цель

Научиться совместно применять переменные, математические операторы и функции объекта Math.

Что нужно сделать

Запишите в переменные x и y координаты двух произвольных точек: x1, y1 — первая точка; x2, y2 — вторая точка. Вычислите площадь прямоугольника, противоположные углы которого представлены указанными точками. Выведите результат с помощью console.log. Напомним, что площадь прямоугольника — это произведение ширины и высоты.

Проверка результата

Для проверки подставляйте разные значения в переменные x1, y1, x2, y2 и смотрите на получившуюся площадь. Примеры для проверки:

для x1 = 2, y1 = 3, x2 = 10, y2 = 5 площадь равна 16;

для x1 = 10, y1 = 5, x2 = 2, y2 = 3 площадь равна 16;

для x1 = -5, y1 = 8, x2 = 10, y2 = 5 площадь равна 45;

для x1 = 5, y1 = 8, x2 = 5, y2 = 5 площадь равна 0;

для x1 = 8, y1 = 1, x2 = 5, y2 = 1 площадь равна 0.

Критерии оценки

Для любых значений координат точек площадь считается корректно.

Советы и рекомендации

Не торопитесь приступать к написанию кода. Попробуйте сначала представить решение на бумаге и всё обдумать. В этом нет ничего страшного, так делают даже серьёзные разработчики с большим опытом работы. Визуализация помогает мозгу быстрее найти решение, часто даже не одно. Перевести такую идею на язык JS или любой другой — это уже дело техники.


Задача 2

Цель

Научиться округлять и точно сравнивать дробные части чисел.

Что нужно сделать

Вычислите дробные части чисел a и b с точностью n. Выведите получившиеся числа с помощью console.log. Выведите результаты их сравнения (>, <, ≥, ≤, ===, ≠) с помощью console.log.

Проверка результата

Для проверки подставляйте разные значения переменных a, b и n и проверяйте получившийся результат. Сравнения должны давать соответствующий результат true или false, в зависимости от получившихся дробных частей.

Примеры для проверки

Для a = 13,123456789, b = 2,123, n = 5 дробные части: 12345, 12300.

Для a = 13,890123, b = 2,891564, n = 2 дробные части: 89, 89.

Для a = 13,890123, b = 2,891564, n = 3 дробные части: 890, 891.

Критерии оценки

Для любых значений a, b и n корректно вычисляются дробные части и выводятся результаты сравнения.

Советы и рекомендации

Здесь нужно активно использовать функции объекта Math. Работу с дробными числами всегда лучше пытаться свести к работе с целыми, так как это более надёжно и удобно.


Задача 3

Цели

Попрактиковаться в написании универсального кода, поддерживающего различные ситуации. Научиться применять Math.random и другие функции объекта Math.

Что нужно сделать

Напишите генератор двух случайных чисел в диапазоне между n и m включительно. Учтите, что n и m могут быть отрицательными, а также может быть n > m или n < m.

Выведите два произвольных числа в консоль с помощью console.log.

Сравните два полученных числа. Выведите результаты их сравнения >, <, ≥, ≤, ===, ≠ с помощью console.log.


Проверка результата

Для проверки подставляйте различные значения m и n и смотрите на корректность результата. Так как числа случайные, для одного набора входных параметров рекомендуется запустить код 5–10 раз. Примеры чисел m и n, для которых алгоритм должен корректно работать:

n = 0, m = 100;

n = 2, m = 5;

n = 100, m = −5;

n = -3, m = −10.
