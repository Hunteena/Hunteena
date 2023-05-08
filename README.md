## Добрый день!

Будем знакомы, меня зовут Нина Сперанская. 👋

Я **Python-разработчик** с опытом работы во фреймворках Django, Django REST framework, Flask с использованием Celery, Git, Docker. Изучаю FastAPI.

Также интересуюсь **Data Engineering**, знаю SQL, понимаю процессы ETL.


## Проекты:


### Backend сайтов
* **Индивидуально**  

  * **Сайт аренды квартир**   
    *Стек: Django/DRF, Swagger, Docker, Git/GitHub.*  
    [Ссылка на репозиторий](https://github.com/Hunteena/apartmentsNN)   
    <details><summary>Подробнее</summary>    
    
    (Сайт в процессе разработки)  
    Возможность оставить онлайн-заявку.  
    Подробная административная панель.  
    Отправка почты.
    Логирование, задачи по расписанию.  
    Docker для локального развёртывания проекта (для фронтенда).  
    В дальнейшем планируется unit-тестирование и деплой.  
    </details>

    
* **В команде** 
  * **Сайт благотворительного центра**    
    *Стек: Django/DRF, Celery, Swagger, Docker, Git/GitLab.*  
    [Описание проекта на Behance](https://www.behance.net/gallery/168737717/solnechnyj-krug)  
    <details><summary>Подробнее</summary>        
    
    (Сайт в процессе разработки)  
    Изменяемая информация о центре: новости, сборы, волонтёры, проекты.  
    Личный кабинет пользователя.  
    Интернет-магазин благотворительных товаров.  
    </details>  
  
  * **Сайт карточной игры Twelve**  
    *Стек: Django/DRF, Pytest, Swagger, Docker, Git/GitHub.*  
    [Ссылка на репозиторий](https://github.com/apodisation13/cardgame)  
    <details><summary>Подробнее</summary>     
    
    [card-game.ru](https://card-game.ru)  
    Коллекционная карточная игра    
    </details>
  
### Тестовые задания

* **Поиск пути между страницами Википедии**  
  <details><summary>Задание</summary>  

  * входные данные: 2 ссылки на wikipedia (можно из файла, можно из консоли вводить)
  * ссылки за пределами wikipedia путем не считаются
  * вручную от одной страницы до второй можно дойти за 3 клика
  * необходимо показать полный путь как пройти от ссылки 1 до ссылки 2
  * отображение пути должно для каждого шага содержать текст (полное предложение, в котором эта ссылка найдена) и ссылку на следующую страницу
  * отображать это можно как в консоли, так и в web
  * дополнительно можно вести лог файл со всеми страницами, что были посещены при поиске
  
  *Пример работы*  

  исходные ссылки:  
  стартовая - https://ru.wikipedia.org/wiki/Xbox_360_S  
  конечная - https://ru.wikipedia.org/wiki/Nintendo_3DS

  ожидаемый вывод:  
  1------------------------  
  И 15 июня 2010 года Microsoft подтвердили их на выставке E³, объявив о прекращении производства старых версий Xbox 360 и скором старте продаж усовершенствованной версии консоли.
  https://ru.wikipedia.org/wiki/Electronic_Entertainment_Expo  
  2-------------------------  
  Это совпало с появлением нового поколения консолей, в частности с выпуском Sega Saturn, и анонсами предстоящих релизов PlayStation, Virtual Boy и Neo Geo CD.
  https://ru.wikipedia.org/wiki/Virtual_Boy  
  3-------------------------  
  Стереоскопическая технология в игровых приставках вновь появилась в более поздние годы и имела больший успех, включая портативную игровую приставку Nintendo 3DS
  https://ru.wikipedia.org/wiki/Nintendo_3DS  

  результат работы:
  github + readme файл с описание логики
  либо файл скрипта + readme файл с описание логики

  </details>  

  *Стек: Python 3.11, requests, beautiful soup, Wiki API.*
  
  [Решение](https://github.com/Hunteena/wikipath)  


* **Тестовое задание по графовым базам данных**  
  <details><summary>Задание</summary>  

  * Установить графовую базу из списка https://db-engines.com/en/ranking/graph+dbms  
     * Предпочтительные - neo4j, nebula, arangodb
     * Предпочтительный язык запросов - cypher  
  * Создать ipynb ноутбук, в котором:
  * Считать данные из источника https://disk.yandex.ru/d/s6wWqd8Ol_5IvQ
  * Внести данные из таблицы в графовую БД
  * Построить графовое представление в БД, осуществить несколько запросов на языке запросов к графовой БД
  * Найти взаимосвязи визуально и с помощью алгоритмов (алгоритмы на ваше усмотрение)
  * Написать rest сервис на python к графовой БД в котором на вход поступает ФИО, на выходе graphml или json
  * Результаты представить на гитхаб и в виде кода + небольшой презентации
  * Срок выполнения задания - около 10 дней, если вы не успеваете можете взять больше времени

  </details>  
  
  *Стек: Neo4j, cypher, Jupiter Notebook, Flask.*
  
  [Решение](https://github.com/Hunteena/neo4j)  



### Учебные проекты в Нетологии

* **Направление «Программирование»**  

  * **API сервиса заказа товаров для розничных сетей**  
    *Стек: Django/DRF, Pytest, Swagger, Celery, Docker, Git/GitHub.*  
    [Ссылка на репозиторий](https://github.com/Hunteena/python-final-diplom)  
    <details><summary>Подробнее</summary>
    REST API (backend) сервиса для автоматизации закупок в розничной сети с товарами от нескольких поставщиков.
    </details>
  
  * **API сайта объявлений**  
    *Стек: Flask, SQLAlchemy, Celery, Docker, Git/GitHub.*  
    [Ссылка на репозиторий](https://github.com/Hunteena/hw_celery)  
    <details><summary>Подробнее</summary>
    REST API (backend) сайта объявлений с авторизацией пользователей и возможностью почтовой рассылки.
    </details>
  
  * **Star Wars & Asyncio**  
    *Стек: Asyncio, SQLAlchemy, Git/GitHub.*  
    [Ссылка на репозиторий](https://github.com/Hunteena/hw_asyncio)  
    <details><summary>Подробнее</summary>
    Асинхронная выгрузка из Star Wars API персонажей Start Wars и их асинхронная загрузка в базу данных.
    </details>
  
  
* **Направление «Аналитика»**  

  * **Итоговый проект курса DWH (Data Warehouse)**  
    *Стек: SQL, PostgreSQL, DBeaver, Pentaho, Git/GitHub.*  
    [Ссылка на репозиторий](https://github.com/Hunteena/DWH_project), [описание базы данных](https://edu.postgrespro.ru/bookings.pdf)  
    <details><summary>Подробнее</summary>
    Создание таблицы измерений и таблицы фактов на основе базы данных.
    </details>
  
  * **Проектная работа по модулю “SQL и получение данных”**  
    *Стек: SQL, PostgreSQL, DBeaver.*  
    [Описание базы данных](https://drive.google.com/file/d/1-4Ue94fEosxeunO7tGl6KId7WvrB0rpc/view?usp=sharing), 
    [SQL-запросы](https://drive.google.com/file/d/1eAVfYyq3DnraQNiNHgCP3r2D9-O8O6tc/view?usp=sharing)  
    <details><summary>Подробнее</summary>
    Получение информации из базы данных об авиаперелётах с помощью SQL-запросов разного уровня сложности (подзапросы, CTE / обобщённые табличные выражения, материализованные представления).
    </details>
  

## Дипломы и сертификаты

- **Python-разработчик с нуля** (программа курса по [ссылке](https://netology.ru/programs/python)), 
диплом о профессиональной переподготовке <!-- ([ссылка]()). -->  
_2022, ООО “Нетология”_

- **Rest API (Intermediate) Certificate** ([ссылка](https://www.hackerrank.com/certificates/a7b31380e4b7))  
_2022, HackerRank_  

- **ETL-разработчик** (программа курса по [ссылке](https://netology.ru/programs/etl-developer)), 
удостоверение о повышении квалификации <!-- ([ссылка](https://drive.google.com/file/d/143MDuKVVKvtsMMb3BpjRCVDtKbibAxMW/view?usp=sharing)). -->    
_2022, ООО “Нетология”_  

- **SQL (Basic) Certificate** ([ссылка](https://www.hackerrank.com/certificates/86b9fdaa561d))  
_2021, HackerRank_  

- **Learning How to Learn: Powerful mental tools to help you master tough subjects** (программа курса по [ссылке](https://www.coursera.org/learn/learning-how-to-learn)), 
сертификат ([ссылка](https://coursera.org/share/6ad6ccaa3354d6a5c77482103b825986))  
_2021, Coursera Inc, Deep Teaching Solutions_  

- **Machine Learning** (программа курса по [ссылке](https://www.coursera.org/learn/machine-learning)), 
сертификат ([ссылка](https://coursera.org/share/472683d93961060ca12f2666f6568306))  
_2018, Coursera Inc, Stanford University_


## Достижения

- Участие в финале Кубка Яндекса по программированию 2022 (Алгоритмы: Марафон)

## Контакты: 

- email: nina.speranskaya35@gmail.com
- Telegram: [@Hunteena](https://t.me/Hunteena)

