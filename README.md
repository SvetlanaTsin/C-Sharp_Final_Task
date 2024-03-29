# **Решение итоговой контрольной по основному блоку** 

## *Задача* 
Написать программу, которая из имеющегося массива строк 
формирует новый массив из строк, длина которых меньше, либо равна 3 символам. 
Первоначальный массив можно ввести с клавиатуры, 
либо задать на старте выполнения алгоритма. 
При решении не рекомендуется пользоваться коллекциями, 
лучше обойтись исключительно массивами.

*Примеры:*
* [“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
* [“1234”, “1567”, “-2”, “computer science”] → [“-2”]  
* [“Russia”, “Denmark”, “Kazan”] → []

## *Решение*

0. Задаем массив строк.

1. **Метод NumberOfElements:** принимает массив строк, возвращает числовое значение. Определяет, сколько в массиве элементов, длина которых равна либо меньше трех символов.

2. **Метод NewArray:** принимает массив строк и возвращает новый массив строк. В методе используется функция NumberOfElements, чтобы определить длину нового массива. Создается переменная j - это индексы нового массива. Функция проходит по изначальному массиву, определяет элементы, которые по длине равны либо меньше трех, и записывает каждый такой элемент в новый массив. 

3. **Метод PrintArray:** это метод void, принимает массив строк и распечатывает его. Для печати в формате, показанном в примерах, использована кодировка Unicode, чтобы задать двойные кавычки. 

4. Вызываем метод NewArray, вызываем метод PrintArray. 