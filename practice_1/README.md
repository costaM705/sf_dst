# Практика 1. Игра: Угадай число

![SkillFactory](../images/sf_logo.png)

## Оглавление
[1. Описание проекта](https://github.com/costaM705/sf_data_science/tree/main/practice_1/README.md#Описание-проекта)   
[2. Какой кейс решаем](https://github.com/costaM705/sf_data_science/tree/main/practice_1/README.md#Какой-кейс-решаем)   
[3. Краткая информация о данных](https://github.com/costaM705/sf_data_science/tree/main/practice_1/README.md#Краткая-информация-о-данных)   
[4. Этапы работы над проектом](https://github.com/costaM705/sf_data_science/tree/main/practice_1/README.md#Этапы-работы-над-проектом)   
[5. Результат](https://github.com/costaM705/sf_data_science/tree/main/practice_1/README.md#Результат)   
[6. Требования для работы](https://github.com/costaM705/sf_data_science/tree/main/practice_1/README.md#Требования-для-работы)   
[7. Выводы](https://github.com/costaM705/sf_data_science/tree/main/practice_1/README.md#Выводы)     

## Описание проекта
Угадать загаданное компьютером число за минимальное количество попыток.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/practice_1/README.md#Оглавление)

## Какой кейс решаем
Нужно написать программу, которая угадывает число за минимальное число попыток.

**Условия соревнования**
* Компьютер загадывает целое число от 0 до 100, и нам его нужно угадать. Под "угадать" подразумевается "написать программу, которая угадывает число".
* Алгоритм учитывает информацию о том, больше ли случайное число или меньше нужного нам.
* Необходимо потратить не более 20 попыток чтобы угадать число.

**Метрика качества**  
Результаты оцениваются по среднему количеству попыток при 1000 повторений.

**Что практикуем**  
Учимся писать хороший код на Python.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/practice_1/README.md#Оглавление)

## Краткая информация о данных
Используется генератор случайных чисел из библиотеки Numpy.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/practice_1/README.md#Оглавление)

## Этапы работы над проектом
1. Пробовал инкремент и декремент с разными шагами.
2. Пробовал алгоритм сужения диапазона.
3. Алгоритм сужения диапазона показал неплохие результаты.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/practice_1/README.md#Оглавление)

## Результат
* Написанная программа угадывает число за 5 шагов или меньше.</br>
* Ноутбук с решением: [practice_1](https://github.com/costaM705/sf_data_science/blob/main/practice_1/practice_1.ipynb).      
* Для обеспечения воспроизводимости кода можно воспользоваться: [requirements.txt](https://github.com/costaM705/sf_data_science/tree/main/practice_1/requirements.txt).

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/practice_1/README.md#Оглавление)

## Требования для работы
* Основной интерпретатор — Python 3.10.
* Дополнительные требования перечислены в requirements.txt (получены командой pip freeze > requirements.txt).
* Установка недостающих компонент:

        pip install -r requirements.txt

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/practice_1/README.md#Оглавление)

## Выводы
Результат достигнут.<br/>
Неплохой результат :)

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/practice_1/README.md#Оглавление)
