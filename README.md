# Метод левых прямоугольников

Разобьем отрезок [a;b] на n частей. Внутри каждого отрезка выберем точку. Высчитываем значения функций в соседних точках. Если f(x_i+1)>f(x_i), то в качестве сторон прямоугольника берем разность аргументов и значение функции в точке x_i. Если f(x_i+1)<f(x_i), то в качестве сторон прямоугольника берем разность аргументов и значение функции в точке x_i+1. Суммируем все полученные площади прямоугольников.
