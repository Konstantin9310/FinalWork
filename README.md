# FinalWork
Задача :

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа.
Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. 
При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Алгоритм решения:
Объявляется два массива: первый и второй - той же длины. 
Потом метод, в котором цикл соразмерный длине массива, внутри цикла проводится проверка условия ( <=3 ), 
если да, то элемент первого массива заносится в count элемент второго массива. 
Переменная count - поочередно закидывает из первого массива во второй и чтобы потом не было пробелов. 
После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1.
И так проверяется до конца.

Графическое представление метода в папке scheme в двух расширениях. Алгоритм по пути cod/Program.cs

