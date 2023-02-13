# Задача: 
## Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

* Примеры: 
["hello", "2", "world", ":-)"] -> ["2", ":-)"]
["1234", "1567", "-2", "computer science"] -> ["-2"]
["Russia", "Denmark", "Kazan"] -> []

**Решение задачи**

Создаем блок ввода исходных данных, согласно заданию и вывода на экран полученного массива.
Создаем функция определения количества элемента массива длина которых меньше какой-то заданной длины length
Для наглядности выводим его на экран с помощью метода PrintArray.

Через цикл счетчиками result = 0 и i = 0 ищем и считаем элементы длина которых меньше либо равна 3-м символам используя функцию CheckArray.
Задаем новую переменной numbers в которую будем присваивать вычисленный элемент массива меньше либо равна 3 символа с помощью метода CheckArray.
Задаем новый массив строк newArrayStrings, который формируется перебором элементов массива arrayStrings, размером, равным переменной numbers.
Формируем новый массива строк с помощью метода NewArray . Cравниваем количество их элементов с переменной length и добавлением в массив newArray элемента, удовлетворяющего условию.
На выходе метода получается заполненный массив строк newArrayStrings что и является решением задачи.
Выводим его на экран с помощью метода PrintArray.