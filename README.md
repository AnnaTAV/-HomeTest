# ИТОГОВАЯ ПРОВЕРОЧНАЯ РАБОТА

* 1. Создать репозиторий на GitHub
* 2. Нарисовать блок схему алгоритма (можно обойтись блок схемой основной содержательной части)
* 3. Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)
* 4. Написать программу решающую поставленную задачу
* 5. Использовать контроль версий в работе над проектом

## ЗАДАЧА
Написать программу, которая из имеющегося массива строк формирут массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. при решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

*Пример:*

["hello", "2", "world", ":-)"] -> ["2", ":-)"]

["1234", "1567", "-2", "computer science"] -> ["-2"]

["Russia", "Denmark", "Kazan"] -> []

## АЛГОРИТМ РЕШЕНИЯ
* Объявляется два массива: одинаковой длины. 
* Внутри цикла делается проверка условия ( <=3 ), если да, то элемент первого массива заносится в count элемента второго массива.
 * Переменная count устанавается, чтобы поочередно проверять данные из первого массива и передавать во второй.
 * После присвоения увеличивается переменная на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.

 ## Графическое представление алгоритма решения находится в папке BlockDiagram

## Задача решена в папке Task