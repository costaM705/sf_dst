# Практика 3. Статистические тесты

![SkillFactory](../images/sf_logo.png)

## Оглавление
[1. Описание проекта](https://github.com/costaM705/sf_data_science/tree/main/practice_3/README.md#Описание-проекта)   
[2. Какой кейс решаем](https://github.com/costaM705/sf_data_science/tree/main/practice_3/README.md#Какой-кейс-решаем)   
[3. Краткая информация о данных](https://github.com/costaM705/sf_data_science/tree/main/practice_3/README.md#Краткая-информация-о-данных)   
[4. Этапы работы над проектом](https://github.com/costaM705/sf_data_science/tree/main/practice_3/README.md#Этапы-работы-над-проектом)   
[5. Результат](https://github.com/costaM705/sf_data_science/tree/main/practice_3/README.md#Результат)   
[6. Требования для работы](https://github.com/costaM705/sf_data_science/tree/main/practice_3/README.md#Требования-для-работы)   
[7. Выводы](https://github.com/costaM705/sf_data_science/tree/main/practice_3/README.md#Выводы)   

## Описание проекта
Используя информацию по мидиям Петербурга и Магадана, которые представлены в виде двух массивов *petersburg* и *magadan*, проверьте данные на нормальность и на наличие взаимосвязи.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/practice_3/README.md#Оглавление)

## Какой кейс решаем
Используя навыки написания кода на Python провести:</br>
1. Анализ на тип распределения данных.
2. Анализ на корреляции данных.
3. Сравнительные тесты.

### Условия: ###
* Решение оформляется только в *Jupiter Notebook*.
* Решение оформляется в соответствии с *ноутбуком-шаблоном*.
* Не следует создавать много ячеек для решения задачи — это проявляет неудобсва при проверке.
* Код на *Python* должен быть читаемым. Не забывать про отступы, разметку и комментарии в коде.
* Выводы по каждому этапу оформляются в формате *Markdown* в отдельной ячейке.

### Метрика качества: ###
* Результаты оцениваются согласно требованиям, указанным к проекту:   

| Количество баллов | Критерии оценивания | 
|---|---| 
| 5 баллов | Данные объединены в DataFrame | 
| 5 баллов | Проведён тест на корреляцию | 
| 7 баллов | Обоснован выбор теста на корреляцию | 
| 3 балла | Сделан правильный вывод по гипотезе | 
| 7 баллов | Проведён тест на сравнение выборок | 
| 7 баллов | Обоснован выбор теста на сравнение | 
| 3 балла | Сделан правильный вывод по гипотезе | 

* Необходимо: ответить на контрольные вопросы, провести дополнительные исследования данных, сделать правильные выводы, сдать проект на проверку, загрузив ноутбук-шаблон со своим решением на GitHub.  
Максимальное количество баллов за задание — **37**.

**Что практикуем**  
* Учимся писать хороший код на Python.
* Учимся отрабатывать взаимодействие с внешними библиотеками статистики и EDA.
* Учимся эффективно работать с IDE VSCode.
* Повышаем квалификацию по методам преобразования и очистки данных.
* Повышаем квалификацию с GitHub.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/practice_3/README.md#Оглавление)

## Краткая информация о данных
Представлены данные в виде двух списков:   
1. 7 значений размеров раковин из региона Санкт-Петербург.
2. 8 значений размеров раковин из региона Магадан.  

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/practice_3/README.md#Оглавление)

## Этапы работы над проектом
* Ознакомление с описанием задачи.
* Знакомство с данными.
* Импорт необходимых библиотек.
* Обработка данных: объединение в единый массив, обработка пропусков.
* Определение типа распределения данных.
* Установление корреляции между выборками.
* Сравнительный анализ выборок.
* Проверка соответствия результата выполнения кода условию, приведенному в метрике качества.
* Проверка соответствия написанного кода стандарту PEP8.
* Оформление проекта.
* Загрузка проекта на GitHub.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/practice_3/README.md#Оглавление)

## Результат
* Ноутбук с решением: [practice_3](https://github.com/costaM705/sf_data_science/blob/main/practice_3/practice_3.ipynb).      
* Для обеспечения воспроизводимости кода можно воспользоваться: [requirements.txt](https://github.com/costaM705/sf_data_science/tree/main/practice_3/requirements.txt).

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/practice_3/README.md#Оглавление)

## Требования для работы
* Основной интерпретатор — Python 3.10.
* Дополнительные требования перечислены в requirements.txt (получены командой pip freeze > requirements.txt).
* Установка недостающих компонент:

        pip install -r requirements.txt

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/practice_3/README.md#Оглавление)

## Выводы
В процессе выполнения кейса:  
* внимательно изучены исходные данные и проанализированы;
* проведена подготовка данных к использованию: объединение и обработка пропусков;
* проведены дополнительные тесты для лучшего понимания представленных данных;
* реализована визуализация дополнительных результатов для выявления взаимосвязей между признаками.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/practice_3/README.md#Оглавление)

