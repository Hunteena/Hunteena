[🇬🇧 Read in English](README.md)

## Добрый день!

Будем знакомы, меня зовут Нина Сперанская. 👋

Я **Python-разработчик** с опытом разработки бэкенда во фреймворках Django/DRF и FastAPI с использованием PostgreSQL, Swagger, Celery (Redis), Git, Docker. 

Также интересуюсь **Data Engineering**, знаю SQL, понимаю процессы ETL.
 
## Проекты:

### Пет-проекты

<details>

<summary>Развернуть</summary>

* **Лучший подарок 🎁**    
    *Стек:  Python, Flask, SQLAlchemy, Docker, Git/GitHub, Telegram API.*  
     
    <details><summary>Подробнее</summary>        
    
    Приложение для создания вишлистов с возможностью для дарителей резервировать подарки на себя.   
    Применяю на практике подходы, описанные в книге [Architecture Patterns with Python by Harry Percival, Bob Gregory](https://www.cosmicpython.com/) (DDD, TDD и другие DD 😉). 
    А также изучаю возможности AI-assisted coding с Cursor.
    </details>  

    [Репозиторий](https://github.com/Hunteena/best-gift) 

</details>

### Python-разработка

<details>

<summary>Развернуть</summary>

* **Автоматизация взаимодействия с маркетплейсом Wildberries**    
    *Стек:  Django, Celery, PostgreSQL, Docker, Nginx, Git/GitHub, Wildberries API, Telegram API.*  
     
    <details><summary>Подробнее</summary>        
    
    API-бот для автоматизации обработки заказов.   
    API-бот для запуска/остановки рекламных кампаний по расписанию.  
    Административная панель с доступом по ролям для управления API-ботами.  
    Telegram-бот для уведомлений.  
    Деплой и поддержка проекта.  
    </details>  

</details>

### Backend сайтов
  
<details>

<summary>Развернуть</summary>

* **В команде**

  * **Внутренняя CRM-система**    
    *Стек:  FastAPI, Swagger, SQL(PostgreSQL), Docker, Git/GitLab, S3 API.*  
     
    <details><summary>Подробнее</summary>        
    
    Разработка схемы БД.  
    SQL без ORM.  
    Unit of Work, хранение файлов в S3.  
    Настройка Docker для локальной и прод-среды.  
    </details>  
 
  * **Сайт центра для слабовидящих**    
    *Стек: Django/DRF, Celery, Swagger, PostgreSQL, Docker, Git/GitLab.*  
    [Сайт проекта](https://ano-mira.ru/) 
    <details><summary>Подробнее</summary>        
    
    Проекты, документы, новости, полезные материалы, команда.  
    Фильтры, поиск.  
    Настройка административной панели.  
    Деплой на сервер.
    </details>  
 
  * **Сайт добрых новостей**    
    *Стек: FastAPI, Swagger, SQL, PostgreSQL, Docker, Git/GitLab.*  
    [Сайт проекта](https://good-deeds-news.com/)  
    <details><summary>Подробнее</summary>        
    
    Микросервисная архитектура.  
    Регистрация пользователей.  
    Статьи, документы, новости, команда, добровольцы.  
    Фильтры, поиск.  
    Разные уровни доступа: для админов, модераторов, обычных пользователей.
    </details>  

  * **Сайт благотворительного центра**    
    *Стек: Django/DRF, Celery, Swagger, PostgreSQL, Docker, Git/GitLab.*  
    [Сайт проекта](https://slkrug.ru/)  
    [Описание проекта на Behance](https://www.behance.net/gallery/168737717/solnechnyj-krug)  
    <details><summary>Подробнее</summary>        
        
    Изменяемая информация о центре: новости, сборы, волонтёры, проекты.  
    Личный кабинет пользователя.  
    Интернет-магазин благотворительных товаров.  
    </details>  
  
  * **Сайт карточной игры Twelve**  
    *Стек: Django/DRF, Pytest, Swagger, PostgreSQL, Docker, Git/GitHub.*  
    [Сайт проекта](https://card-game.ru)  
    [Ссылка на репозиторий](https://github.com/apodisation13/cardgame)   
    <details><summary>Подробнее</summary>     
        
    Коллекционная карточная игра    
    </details>

* **Индивидуально**  

  * **Сайт аренды квартир**   
    *Стек: Django/DRF, Pytest, Swagger, PostgreSQL, Docker, Git/GitHub.*  
    [Ссылка на репозиторий](https://github.com/Hunteena/apartmentsNN)   
    <details><summary>Подробнее</summary>    
    
    (Сайт в процессе разработки)  
    Возможность оставить онлайн-заявку.  
    Подробная административная панель.  
    Отправка почты.
    Логирование, задачи по расписанию.  
    Docker для локального развёртывания проекта (для фронтенда).  
    Unit-тестирование API с помощью Pytest.  
    В дальнейшем планируется деплой на сервер всего проекта и CI/CD.  
    </details>

</details>

### Тестовые задания

<details>

<summary>Развернуть</summary>

* **Калькулятор с использованием только сложения и вычитания**  
  *Стек: Python 3.9, Pytest, Poetry.*
  
  <details><summary>Задание</summary>  
  
  * Базовые функции:
    - `+`  сложение,
    - `-` вычитание, 
    - `/` деление,
    - `*` умножение,
    - `%` остаток от деления,
    - `^x` возведение в степень,
    - `x^1/2` извлечение квадратного корня,
    - решение простых уравнений с одним неизвестным, например, `2 + x = 14`  
        
  * Требования:
    - Используем Python 3.9
    - Использование библиоттек запрещено (в т.ч. импорты базовых модулей по типу decimal или math).
    - Допустимо использовать для реализации только "+" и "-",
    - Ввод значений происходит через терминал.
    - Необходимо сохранять историю (ввод/вывод).
    - Копирование в буфер обмена по клавишам ctrl+c результата вычислений
    - Обработка ошибок и вывод в человеко-читаемом формате
    - Результат вычислений должен иметь погрешность:
      - при int <= 0.5%.
      - при float <= 5%.


  </details>  
  
  [Решение](https://github.com/Hunteena/calculator) 


* **Simple RESTful API for a social networking application**  
  *Stack: Python 3.11, FastAPI, SQL, PostgreSQL, Swagger, Docker.*
  <details><summary>Task</summary>  

  * There should be some form of authentication and registration (JWT, Oauth, Oauth 2.0, etc..)  
  * As a user I need to be able to signup and login  
  * As a user I need to be able to create, edit, delete and view posts  
  * As a user I can like or dislike other users’ posts but not my own  
  * The API needs a UI Documentation (Swagger/ReDoc)  

  </details>    
  
  [Solution](https://github.com/Hunteena/simple_social_network) 

* **Тестовое задание с ипользованием библиотеки Pandas**  
  *Стек: Python 3.11, Pandas, Jupiter Notebook.*
  
  <details><summary>Задание</summary>  

  Время на выполнение задания:
  одни сутки (до 24ч) с момента получения задания и до момента отправки решения задания менеджеру в чат.
  
  * Найти тариф стоимости доставки для каждого склада
  * Найти суммарное количество , суммарный доход , суммарный расход и суммарную прибыль для каждого товара (представить как таблицу со столбцами 'product', 'quantity', 'income', 'expenses', 'profit')
  * Составить табличку со столбцами 'order_id' (id заказа) и 'order_profit' (прибыль полученная с заказа). А также вывести среднюю прибыль заказов
  * Составить табличку типа 'warehouse_name' , 'product','quantity', 'profit', 'percent_profit_product_of_warehouse' (процент прибыли продукта заказанного из определенного склада к прибыли этого склада)
  * Взять предыдущую табличку и отсортировать 'percent_profit_product_of_warehouse' по убыванию, после посчитать накопленный процент. Накопленный процент - это новый столбец в этой табличке, который должен называться 'accumulated_percent_profit_product_of_warehouse'. По своей сути это постоянно растущая сумма отсортированного по убыванию столбца 'percent_profit_product_of_warehouse'.
  * Присвоить A,B,C - категории на основании значения накопленного процента ('accumulated_percent_profit_product_of_warehouse'). Если значение накопленного процента меньше или равно 70, то категория A.  
Если от 70 до 90 (включая 90), то категория Б. Остальное - категория C. Новый столбец обозначить в таблице как 'category'

  <details><summary>Объяснение полей</summary>
   
    ```python
    {
    "order_id": 85787,	# уникальный id заказа  ( int, варьируется в пределах (100, 100000))
    "warehouse_name": "хутор близ Диканьки",	# склад откуда отправился заказ (str)
    "highway_cost": -90,	# стоимость доставки заказа (суммарная стоимости доставки всех продуктов) (int)
    "products": [		# продукты входящие в заказ
    {
    "product": "зеленая пластинка",		# наименования продукта (str)
    "price": 10,	# цена продажи за единицу товара	(int)
    "quantity": 3	# количество проданного товара	(int)
    },
    {
    "product": "зеленая пластинка",	# наименования продукта (str)
    "price": 10,	# цена продажи за единицу товара	(int)
    "quantity": 2	# количество проданного товара (int)
    },
    {
    "product": "билет в Израиль",	# наименования продукта (str)
    "price": 1000,	# цена продажи за единицу товара	(int)
    "quantity": 1	# количество проданного товара (int)
    }
    ]
    },
    ```
  </details>
  <details><summary>Объяснение highway_cost (стоимости доставки)</summary>  
   
    Когда заказ доставляется из склада, то списывается стоимость доставки. У каждого склада есть определенный тариф, определяющий стоимость доставки. Это тариф имеет размерность стоимость доставки на единицу товара.  
    Например для склада "гиперборея" стоимость тарифа составляет 20 рублей на единицу товара.
    Причем тариф не зависит от того какой именно товар мы заказали. Так, если мы заказали 5 зеленых пластинок и 3 билета в Израиль, то стоимость тарифа будет 20*(5+3) = 160 рублей.
  </details>
  <details><summary>Уточнение по виду отчета</summary>  
   
    В поле "products" не обязательно могут быть только уникальные значения наименовая товаров ("product"). Иногда (как в примере выше) названия товаров могут повторяться в поле "products".  
    Однако поле "products" не может быть пустым
  </details>
  <details><summary>Дополнительное пояснение</summary>  
   
    доходом с товара является цена продажи * количество товара  
    расходом является тариф для данного склада * количество товара  
    прибылью является доход - расход
  </details> 
  
  </details>  
  
  [Решение](https://github.com/Hunteena/pandas/blob/main/Pandas.ipynb)  

* **Поиск пути между страницами Википедии**  
  *Стек: Python 3.11, requests, beautiful soup, Wiki API.*
  
  <details><summary>Задание</summary>  

  * входные данные: 2 ссылки на wikipedia (можно из файла, можно из консоли вводить)
  * ссылки за пределами wikipedia путем не считаются
  * вручную от одной страницы до второй можно дойти за 3 клика
  * необходимо показать полный путь как пройти от ссылки 1 до ссылки 2
  * отображение пути должно для каждого шага содержать текст (полное предложение, в котором эта ссылка найдена) и ссылку на следующую страницу
  * отображать это можно как в консоли, так и в web
  * дополнительно можно вести лог файл со всеми страницами, что были посещены при поиске
  
    <details><summary>Пример работы</summary>  
  
    исходные ссылки:  
    стартовая - https://ru.wikipedia.org/wiki/Xbox_360_S  
    конечная - https://ru.wikipedia.org/wiki/Nintendo_3DS
  
    ожидаемый вывод:
    ```
    1------------------------  
    И 15 июня 2010 года Microsoft подтвердили их на выставке E³, объявив о прекращении производства старых версий Xbox 360 и скором старте продаж усовершенствованной версии консоли.
    https://ru.wikipedia.org/wiki/Electronic_Entertainment_Expo  
    2-------------------------  
    Это совпало с появлением нового поколения консолей, в частности с выпуском Sega Saturn, и анонсами предстоящих релизов PlayStation, Virtual Boy и Neo Geo CD.
    https://ru.wikipedia.org/wiki/Virtual_Boy  
    3-------------------------  
    Стереоскопическая технология в игровых приставках вновь появилась в более поздние годы и имела больший успех, включая портативную игровую приставку Nintendo 3DS
    https://ru.wikipedia.org/wiki/Nintendo_3DS  
    ```
  
    результат работы:
    github + readme файл с описание логики
    либо файл скрипта + readme файл с описание логики
    </details>

  </details>  

  [Решение](https://github.com/Hunteena/wikipath)  


* **Тестовое задание по графовым базам данных**  
  *Стек: Neo4j, cypher, Jupiter Notebook, Flask.*
  
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
  
  [Решение](https://github.com/Hunteena/neo4j)  

</details>


### Учебные проекты в Нетологии

<details>

<summary>Развернуть</summary>

* **Направление «Программирование»**  

  * **API сервиса заказа товаров для розничных сетей**  
    *Стек: Django/DRF, Pytest, Swagger, PostgreSQL, Celery, Docker, Git/GitHub.*  
    [Ссылка на репозиторий](https://github.com/Hunteena/python-final-diplom)  
    <details><summary>Подробнее</summary>
    REST API (backend) сервиса для автоматизации закупок в розничной сети с товарами от нескольких поставщиков.
    </details>
  
  * **API сайта объявлений**  
    *Стек: Flask, SQLAlchemy, Celery, PostgreSQL, Docker, Git/GitHub.*  
    [Ссылка на репозиторий](https://github.com/Hunteena/hw_celery)  
    <details><summary>Подробнее</summary>
    REST API (backend) сайта объявлений с авторизацией пользователей и возможностью почтовой рассылки.
    </details>
  
  * **Star Wars & Asyncio**  
    *Стек: Asyncio, SQLAlchemy, PostgreSQL, Git/GitHub.*  
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

- Прошла в финал Кубка Яндекса по программированию 2022 (Алгоритмы: Марафон)

## Контакты: 

- email: nina.speranskaya35@gmail.com
- Telegram: [@Hunteena](https://t.me/Hunteena)

