# Проект 1. Анализ резюме из HeadHunter

![SkillFactory](../images/sf_logo.png)

## Оглавление

[1. Введение](https://github.com/costaM705/sf_data_science/tree/main/project_1/README.md#Введение)   
[2. Описание задачи](https://github.com/costaM705/sf_data_science/tree/main/project_1/README.md#Описание-задачи)   
[3. Описание данных](https://github.com/costaM705/sf_data_science/tree/main/project_1/README.md#Описание-данных)   
[4. Результат](https://github.com/costaM705/sf_data_science/tree/main/project_1/README.md#Результат)   
[5. Требования для работы](https://github.com/costaM705/sf_data_science/tree/main/project_1/README.md#Требования-для-работы)   
[6. Выводы](https://github.com/costaM705/sf_data_science/tree/main/project_1/README.md#Выводы)   

## Введение

 Компания HeadHunter хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе. Однако прежде чем построить модель, данные необходимо преобразовать, исследовать и очистить. В этом и заключается цель данного проекта.

 :arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_1/README.md#Оглавление)      

## Описание задачи

Проект состоит из четырёх частей:   

1. Базовый анализ структуры данных.   
2. Преобразование данных.   
3. Разведывательный анализ.   
4. Очистка данных.   

Каждая часть состоит из блока практических заданий, которые необходимо выполнить в jupyter-ноутбуке.<br/>     

Требования к оформлению ноутбука-решения:
* Решение оформляется только в Jupyter Notebook.
* Решение оформляется в соответствии с ноутбуком-шаблоном.
* Каждое задание выполняется в отдельной ячейке, выделенной под задание (в шаблоне они помечены как ваш код здесь). Не следует создавать множество ячеек для решения задачи — это создаёт неудобства при проверке.
* Код для каждого задания оформляется в одной-двух jupyter-ячейках (не стоит создавать множество ячеек для решения задачи, это усложняет проверку).
* Решение должно использовать только пройденный материал: переменные, основные структуры данных (списки, словари, множества), циклы, функции, библиотеки numpy, pandas, matplotlib, seaborn, plotly. Если вы думаете, что для решения необходимо воспользоваться сторонними библиотеками или инструментами (например Excel), другими языками программирования или неизученными конструкциями, вы ошибаетесь :) Все задания решаются с помощью уже знакомых методов.
* Код должен быть читаемым и понятным: имена переменных и функций отражают их сущность, важно избегать многострочных конструкций и условий.
* Пользуйтесь руководством PEP 8.
* Графики оформляются в соответствии с теми правилами, которые мы приводили в модуле по визуализации данных.
* Обязательное требование: графики должны содержать название, отражающее их суть, и подписи осей.
* Выводы к графикам оформляются в формате Markdown под самим графиком в отдельной ячейке (в шаблоне они помечены как ваши выводы здесь). Выводы должны быть представлены в виде небольших связанных предложений на русском языке.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_1/README.md#Оглавление)      

## Описание данных

В проекте используется база резюме, выгруженная с сайта поиска вакансий hh.ru.        
Датасет содержит 44744 обезличенные записи по 12 признакам:                     
* Пол, возраст — пол и возраст соискателя;                    
* ЗП — ожидаемая заработная плата;                                      
* Ищет работу на должность — сведения о желаемой должности;                 
* Город, переезд, командировки — город проживания соискателя, его готовность к переезду и командировкам;              
* Занятость — желаемая занятость в виде одной из категорий: полная занятость, частичная занятость, проектная работа, волонтерство, стажировка;                    
* График — желаемый график работы в виде одной из категорий: полный день, сменный график, гибкий график, удаленная работа, вахтовый метод;                           
* Опыт работы — сведения об опыте работы соискателя;             
* Последнее/нынешнее место работы — сведения последнем/нынешнем месте работы;              
* Последняя/нынешняя должность — сведения о последней/нынешней должности;             
* Образование и ВУЗ — уровень образования соискателя и наименование законченного учебного заведения;               
* Обновление резюме — дата и время последнего обновления резюме соискателем;             
* Авто — наличие у соискателя автомобиля.             

Исходный датасет можно скачать по [ссылке](https://drive.google.com/file/d/1ikA_Ht45fXD2w5dWZ9sGTSRl-UNeCVub/view?usp=share_link)     
Файл [ExchangeRates.zip](https://github.com/costaM705/sf_data_science/tree/main/project_1/data/ExchangeRates.zip) содержит сведения о курсах валют.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_1/README.md#Оглавление)        

## Результат

* Ноутбук с решением: [project_1](https://github.com/costaM705/sf_data_science/blob/main/project_1/project_1.ipynb).
* Для обеспечения воспроизводимости кода можно воспользоваться: [requirements.txt](https://github.com/costaM705/sf_data_science/tree/main/project_1/requirements.txt).

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_1/README.md#Оглавление)         

## Требования для работы

* Основной интерпретатор — Python 3.10.
* Дополнительные требования перечислены в requirements.txt (получены командой pip freeze > requirements.txt).
* Установка недостающих компонент:

        pip install -r requirements.txt

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_1/README.md#Оглавление)         

## Выводы

В данном проекте была проведена работа по исследованию и очистке данных на примере датасета, содержащего резюме соискателей с сайта поиска вакансий hh.ru.
Было проведено преобразование данных путем формирования новых информативных признаков и удаления исходных, не несущих полезной информации. Выполнено исследование зависимостей данных с использованием визуализации (библиотеки matplotlib и seaborn). Проведена очистка данных: удалены дублированные записи, проведена обработка пропусков в данных, ликвидированы выбросы.

:arrow_up:[к оглавлению](https://github.com/costaM705/sf_data_science/tree/main/project_1/README.md#Оглавление)   


