**Задача**

1. Создать репозиторий на github
2. Нарисовать блок-схему алгоритма
3. Снабдить репо файлом Readme.md с подробным описанием
4. Написать программу, решающую поставленную задачу
5. Использовать контроль версий над этим проектом, с минимум 3-4 коммита на 2,3,4 блоках.

*Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами*

Описание алгоритма решения:
Первое: объявляется два массива: изначальный и вторый одинаковой длины. Далее метод, в котором цикл соразмерный длине массива, внутри цикла проверка условия ( <=3 ), если да, элемент первого массива заносится в count элемент второго массива. Переменная count, чтобы поочередно закидывать из первого массива во второй и, чтобы потом не было пробелов. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до победного.