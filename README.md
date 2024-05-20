# version_control
## Задание : 
### Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами
## Алгоритм решения:
### Для начала создаются два массива - исходный и вторый той же длины. Далее следует метод, в котором цикл соизмеримый длине массива. Внутри данного цикла проверяется условие ( <=3 ). В случае, "да" - элемент первого массива заносится в "count" элемент второго массива. Переменная "count" используется для того, чтобы по очереди закидывать из первого массива во второй без пробелов. В дальнейшем, после присвоения, переменная "count" увеличивается на единицу и возвращается к циклу "for", в котором "i" тоже увеличивается на единицу. Проверка идет до конца.