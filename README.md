**Задача:**

Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

**Описание решения задачи:**

Для начало объявляем два массива одной длины, создаем метод *"SortingArray"* внутри него создаем цикл *"for"* который равен длине массива, внутри которого проверка условия *"if"* ( <=3 ), если *"да"* элемент первого массива заносится в переменную *"count"*который является элементом второго массива. Созданная переменная *count* нужна для того чтобы поочередно закидывать из первого массива во второй массив без пропуска элементов массива. После присвоения увеличивается переменная *count* на 1 и возвращается к циклу "*for"* в котором *"i"* увеличивается на 1. И так цикл работает по всей длине массива.

Изображение блок-схемы программы находится в файле blockDiagram.png
