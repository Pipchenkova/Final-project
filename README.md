                Здравствуйте!

        Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.
        Примеры: [“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”] [“1234”, “1567”, “-2”, “computer science”] → [“-2”] [“Russia”, “Denmark”, “Kazan”] → []

1 Начнём с состовленя блок схемы . 2 Схема представлена в формате jpg . 3 Создаём файлы с игнором и описанием 4 Создаём папку для программы 5 Алгоритм решения : 5.1 объявляем два массива 5.2 создаём метод, в котором цикл соразмерный длине массива, внутри цикла проверка условия ( <=3 ) 5.3 если элемент соответствует условию то элемент первого массива заносится в count элемент второго массива. 5.4 После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.