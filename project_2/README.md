# Проект 2. Анализ вакансий из HeadHunter

## Оглавление

[1. Описание проекта](https://github.com/costaM705/sf_data_science/tree/main/project_2/README.md#Описание_проекта)   
[2. Какой кейс решаем](https://github.com/costaM705/sf_data_science/tree/main/project_2/README.md#Какой_кейс_решаем)   
[3. Описание данных](https://github.com/costaM705/sf_data_science/tree/main/project_2/README.md#Описание_данных)
[4. Этапы работы над проектом](https://github.com/costaM705/sf_data_science/tree/main/project_2/README.md#Этапы_работы_над_проектом)          
[5. Результат](https://github.com/costaM705/sf_data_science/tree/main/project_2/README.md#Результат)          
[6. Выводы](https://github.com/costaM705/sf_data_science/tree/main/project_2/README.md#Выводы)       


## Описание_проекта

Провести анализ данных и понять, что из себя представляют данные и насколько они соответствуют целям проекта для создания модели машинного обучения по подбору вакансий для IT-специалистов.

 :arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_2/README.md#Оглавление)      


## Какой_кейс_решаем

1. Знакомство с данными<br/>
2. Предварительный анализ данных<br/>
3. Детальный анализ вакансий<br/>
4. Анализ работодателей<br/>
5. Предметный анализ<br/>

Условия задания:
* Каждая часть состоит из блока практических заданий, которые необходимо выполнить в jupiter-ноутбуке.
* оутбук необходимо оформить на основе предоставленного шаблона и требований.
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

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_2/README.md#Оглавление)      


## Описание_данных

* Таблица VACANCIES хранит данные по вакансиям.
* Таблица AREAS является справочником, в котором хранятся коды городов и их названия.
* Таблица EMPLOYERS является справочником со списокм работодателей.
* Таблица INDUSTRIES является справочником вариантов сфер детельности работодателей.
* Таблица EMPLOYERS_INDUSTRIES - дополнительная таблица, которая существует для связи между работодателями и сферами их деятельности.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_2/README.md#Оглавление)        


## Этапы_работы_над_проектом

* Исследование структуры данных.
* Преобразование данных.
* Исследование зависимостей в данных.
* Очистка данных.
* Оформление GitHub.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_2/README.md#Оглавление)        


## Результат

Ноутбук с решением: [Project_2_vacancies_analysis_from_HeadHunter.ipynb](https://github.com/costaM705/sf_data_science/blob/main/project_2/project_2_vacancies_analysis_from_HeadHunter.ipynb).      
Для обеспечения воспроизводимости кода можно воспользоваться: [requirements.txt](https://github.com/costaM705/sf_data_science/tree/main/project_2/requirements.txt).

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_2/README.md#Оглавление)         


## Выводы

В данном проекте была проведена работа по исследованию и очистке данных на примере датасета, содержащего вакансии с сайта поиска вакансий hh.ru.
Решена часть бизнес-задачи и применена роль работника кадрового агенства.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_2/README.md#Оглавление)   


