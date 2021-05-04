# Логические основы интеллектуальных систем
## Лабораторная работа №1
#### Вариант C --- Проверить, является ли формула СКНФ
Запуск: `npm run lab1`

Запуск тестов: `npm run test1`

Вход --- булева формула, содержащая в себе:
* Переменные (буквы английского алфавита в верхнем регистре)
* Константы (`1` и `0`)
* Логические операторы:
    * Конъюнкция: /\
    * Дизъюнкция: \/
    * Отрицание: !
    * Импликация: ->
    * Эквиваленция: ~
    
Выход --- `true`, если формула является СКНФ, `false` и описание ошибки, если не является СКНФ
## Лабораторная работа №2
#### Вариант 2 --- Проверить, является ли формула тавтологией
Запуск: `npm run lab2` 

Запуск тестов: `npm run test2`

Вход --- аналогичен первой лабораторной работе

Выход --- таблица истинности формулы и `true`, если формула является тавтологией, 
и `false`, если не является