# Проект 3. Рейтинг отеля по данным сайта Booking.
EDA + Feature Engineering. Соревнование на Kaggle

![SkillFactory](../images/sf_logo.png)

## Оглавление

[1. Описание проекта](https://github.com/costaM705/sf_data_science/tree/main/project_3/README.md#Описание-проекта)   
[2. Какой кейс решаем](https://github.com/costaM705/sf_data_science/tree/main/project_3/README.md#Какой-кейс-решаем)   
[3. Описание данных](https://github.com/costaM705/sf_data_science/tree/main/project_3/README.md#Описание-данных)   
[4. Этапы работы над проектом](https://github.com/costaM705/sf_data_science/tree/main/project_3/README.md#Этапы-работы-над-проектом)   
[5. Результат](https://github.com/costaM705/sf_data_science/tree/main/project_3/README.md#Результат)   
[6. Требования для работы](https://github.com/costaM705/sf_data_science/tree/main/project_3/README.md#Требования-для-работы)         
[7. Выводы](https://github.com/costaM705/sf_data_science/tree/main/project_3/README.md#Выводы)   

## Описание проекта

Провести анализ данных и понять, что из себя представляют данные и насколько они соответствуют целям проекта для создания модели машинного обучения по подбору вакансий для IT-специалистов.

 :arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_3/README.md#Оглавление)      


## Какой кейс решаем

1. Знакомство с данными   
2. Предварительный анализ данных   
3. Детальный анализ вакансий   
4. Анализ работодателей   
5. Предметный анализ   

Условия задания:
* Каждая часть состоит из блока практических заданий, которые необходимо выполнить в jupiter-ноутбуке.
* Ноутбук необходимо оформить на основе предоставленного шаблона и требований.
* Отправить ментору для code-ревью.

Метрики качества:
* Решение оформляется только в Jupyter Notebook.
* Решение оформляется в соответствии с ноутбуком-шаблоном.
* Каждое задание выполняется в отдельной ячейке, выделенной под задание.
* Текст SQL-запросов и код на Python должны быть читаемыми.
* Выводы по каждому этапу оформляются в формате Markdown в отдельной ячейке.
* Выводы можно дополнительно проиллюстрировать с помощью графиков.
* Не забудьте удалить ячейку с данными соединения перед фиксацией работы в GitHub.

Что практикуем:
* Работу с данными и выполнение SQL-запросов.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_3/README.md#Оглавление)      

## Описание данных

* Таблица VACANCIES хранит данные по вакансиям.
* Таблица AREAS является справочником, в котором хранятся коды городов и их названия.
* Таблица EMPLOYERS является справочником со списокм работодателей.
* Таблица INDUSTRIES является справочником вариантов сфер детельности работодателей.
* Таблица EMPLOYERS_INDUSTRIES - дополнительная таблица, которая существует для связи между работодателями и сферами их деятельности.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_3/README.md#Оглавление)        


## Этапы работы над проектом

* Исследование структуры данных.
* Преобразование данных.
* Исследование зависимостей в данных.
* Очистка данных.
* Оформление GitHub.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_3/README.md#Оглавление)        

## Результат

Ноутбук с решением: [project_2](https://github.com/costaM705/sf_data_science/blob/main/project_3/project_3.ipynb).      
Для обеспечения воспроизводимости кода можно воспользоваться: [requirements.txt](https://github.com/costaM705/sf_data_science/tree/main/project_3/requirements.txt).

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_3/README.md#Оглавление)         

## Требования для работы

* Основной интерпретатор — Python 3.10.
* Дополнительные требования перечислены в requirements.txt (получены командой pip freeze > requirements.txt).
* Установка недостающих компонент:

        pip install -r requirements.txt

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_3/README.md#Оглавление)         

## Выводы

В данном проекте была проведена работа по исследованию и очистке данных на примере датасета, содержащего вакансии с сайта поиска вакансий hh.ru.
Решена часть бизнес-задачи и применена роль работника кадрового агенства.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_3/README.md#Оглавление)   


