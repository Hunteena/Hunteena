[🇷🇺 Читать на русском](README_RU.md)

## Hello!

Nice to meet you, my name is Nina Speranskaya. 👋

I am a **Python Developer** experienced in backend development using Django/DRF and FastAPI, with PostgreSQL, Swagger, Celery (Redis), Git, and Docker. 

I am also interested in **Data Engineering**, know SQL, and understand ETL processes.
 
## Projects:

### Pet Projects

<details>

<summary>Expand</summary>

* **Best Gift 🎁**    
    *Stack: Python, Flask, SQLAlchemy, Docker, Git/GitHub, Telegram API.*  
     
    <details><summary>Details</summary>        
    
    A wishlist application that allows gift-givers to reserve gifts for themselves.  
    Applying architectural approaches from the book [Architecture Patterns with Python by Harry Percival, Bob Gregory](https://www.cosmicpython.com/) (DDD, TDD, and other DDs 😉).  
    Also exploring AI-assisted coding capabilities with Cursor.
    </details>  

    [Repository](https://github.com/Hunteena/best-gift) 

</details>

### Python Development

<details>

<summary>Expand</summary>

* **Wildberries Marketplace Automation**    
    *Stack: Django, Celery, PostgreSQL, Docker, Nginx, Git/GitHub, Wildberries API, Telegram API.*  
     
    <details><summary>Details</summary>        
    
    API bot for automated order processing.   
    API bot for scheduling the launch/pause of advertising campaigns.  
    Role-based administrative panel to manage API bots.  
    Telegram bot for notifications.  
    Deployment and project maintenance.  
    </details>  

</details>

### Web Backend
  
<details>

<summary>Expand</summary>

* **Team Projects**

  * **Internal CRM System**    
    *Stack: FastAPI, Swagger, SQL (PostgreSQL), Docker, Git/GitLab, S3 API.*  
     
    <details><summary>Details</summary>        
    
    Database schema design.  
    Raw SQL without ORM.  
    Unit of Work pattern, file storage in S3.  
    Docker configuration for local and production environments.  
    </details>  
 
  * **Center for the Visually Impaired Website**    
    *Stack: Django/DRF, Celery, Swagger, PostgreSQL, Docker, Git/GitLab.*  
    [Project Website](https://ano-mira.ru/) 
    <details><summary>Details</summary>        
    
    Projects, documents, news, educational materials, team.  
    Filters and search.  
    Admin panel configuration.  
    Server deployment.
    </details>  
 
  * **Good Deeds News Website**    
    *Stack: FastAPI, Swagger, SQL, PostgreSQL, Docker, Git/GitLab.*  
    [Project Website](https://good-deeds-news.com/)  
    <details><summary>Details</summary>        
    
    Microservices architecture.  
    User registration and authentication.  
    Articles, documents, news, team, volunteers.  
    Filters and search.  
    Role-based access levels: administrators, moderators, regular users.
    </details>  

  * **Charity Center Website**    
    *Stack: Django/DRF, Celery, Swagger, PostgreSQL, Docker, Git/GitLab.*  
    [Project Website](https://slkrug.ru/)  
    [Project on Behance](https://www.behance.net/gallery/168737717/solnechnyj-krug)  
    <details><summary>Details</summary>        
        
    Dynamic center information: news, fundraisers, volunteers, projects.  
    User account area.  
    E-commerce store for charitable goods.  
    </details>  
  
  * **Twelve Card Game Website**  
    *Stack: Django/DRF, Pytest, Swagger, PostgreSQL, Docker, Git/GitHub.*  
    [Project Website](https://card-game.ru)  
    [Repository Link](https://github.com/apodisation13/cardgame)   
    <details><summary>Details</summary>     
        
    Collectible card game.    
    </details>

* **Individual Projects**  

  * **Apartment Rental Website**   
    *Stack: Django/DRF, Pytest, Swagger, PostgreSQL, Docker, Git/GitHub.*  
    [Repository Link](https://github.com/Hunteena/apartmentsNN)   
    <details><summary>Details</summary>    
    
    (Website in development)  
    Online booking/inquiry submission.  
    Comprehensive administration panel.  
    Email notifications.  
    Logging and scheduled background tasks.  
    Docker for local deployment (for frontend).  
    API unit testing with Pytest.  
    Full project server deployment and CI/CD planned for the future.  
    </details>

</details>

### Coding Challenges & Test Tasks

<details>

<summary>Expand</summary>

* **Calculator Using Only Addition and Subtraction**  
  *Stack: Python 3.9, Pytest, Poetry.*
  
  <details><summary>Task Description</summary>  
  
  * Basic functions:
    - `+` addition,
    - `-` subtraction, 
    - `/` division,
    - `*` multiplication,
    - `%` modulo,
    - `^x` exponentiation,
    - `x^1/2` square root,
    - solving linear equations with one unknown, e.g., `2 + x = 14`  
        
  * Requirements:
    - Python 3.9
    - No external or standard computational libraries allowed (including built-in modules like `decimal` or `math`).
    - Only `+` and `-` allowed in arithmetic implementation.
    - Terminal input/output.
    - Preserving history (input/output).
    - Copying result to clipboard via Ctrl+C.
    - Human-readable error handling.
    - Margin of error:
      - integer results: <= 0.5%.
      - float results: <= 5%.

  </details>  
  
  [Solution](https://github.com/Hunteena/calculator) 


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


* **Test Task Using Pandas**  
  *Stack: Python 3.11, Pandas, Jupyter Notebook.*
  
  <details><summary>Task Description</summary>  

  Time limit: 24 hours from assignment receipt to submission.
  
  * Calculate delivery shipping rates for each warehouse.
  * Compute total quantity, total income, total expenses, and total profit for each product (formatted as a table with columns: 'product', 'quantity', 'income', 'expenses', 'profit').
  * Generate a table with columns 'order_id' and 'order_profit', and calculate average order profit.
  * Generate a table with columns 'warehouse_name', 'product', 'quantity', 'profit', 'percent_profit_product_of_warehouse' (share of product profit ordered from a specific warehouse relative to that warehouse's total profit).
  * Sort the previous table by 'percent_profit_product_of_warehouse' descending, then compute the cumulative percentage in a new column 'accumulated_percent_profit_product_of_warehouse'.
  * Assign A, B, C categories based on the cumulative percentage ('accumulated_percent_profit_product_of_warehouse'):
    - <= 70: Category A.
    - 70 to 90 (inclusive): Category B.
    - Remaining: Category C.
    Add this column as 'category'.

  <details><summary>Field Definitions</summary>
   
    ```python
    {
    "order_id": 85787,	# unique order ID (int, ranges between 100 and 100000)
    "warehouse_name": "хутор близ Диканьки",	# warehouse name from which order was shipped (str)
    "highway_cost": -90,	# total shipping cost of the order (sum of shipping costs for all products) (int)
    "products": [		# products in the order
    {
    "product": "зеленая пластинка",		# product name (str)
    "price": 10,	# unit sale price (int)
    "quantity": 3	# quantity sold (int)
    },
    {
    "product": "зеленая пластинка",	# product name (str)
    "price": 10,	# unit sale price (int)
    "quantity": 2	# quantity sold (int)
    },
    {
    "product": "билет в Израиль",	# product name (str)
    "price": 1000,	# unit sale price (int)
    "quantity": 1	# quantity sold (int)
    }
    ]
    },
    ```
  </details>
  <details><summary>Delivery Cost (highway_cost) Explanation</summary>  
   
    When an order is shipped from a warehouse, shipping costs apply. Each warehouse has a specific rate per product unit.  
    For instance, warehouse "гиперборея" has a rate of 20 rubles per product unit.  
    The rate does not depend on the specific product item. For example, for 5 green records and 3 tickets to Israel, the shipping cost is 20 * (5 + 3) = 160 rubles.
  </details>
  <details><summary>Report Format Clarification</summary>  
   
    The "products" list does not necessarily contain unique product names ("product"). Sometimes (as in the example above), product names can repeat in "products".  
    However, "products" cannot be empty.
  </details>
  <details><summary>Additional Details</summary>  
   
    product income = unit price * quantity  
    product expense = warehouse shipping rate * quantity  
    product profit = income - expense
  </details> 
  
  </details>  
  
  [Solution](https://github.com/Hunteena/pandas/blob/main/Pandas.ipynb)  


* **Shortest Path Search Between Wikipedia Pages**  
  *Stack: Python 3.11, requests, Beautiful Soup, Wiki API.*
  
  <details><summary>Task Description</summary>  

  * Input: 2 Wikipedia URLs (from file or console input).
  * External links outside Wikipedia are not considered valid paths.
  * The second page is reachable from the first in 3 clicks manually.
  * Output the complete path from URL 1 to URL 2.
  * Each step should display text (the full sentence containing the link) and the URL of the next page.
  * Display in console or web interface.
  * Optional: maintain a log file of all pages visited during the search.
  
    <details><summary>Sample Output</summary>  
  
    Initial URLs:  
    Start — https://ru.wikipedia.org/wiki/Xbox_360_S  
    Target — https://ru.wikipedia.org/wiki/Nintendo_3DS  
  
    Expected output:
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
  
    Deliverable:
    GitHub repository + README with architecture/logic explanation, or script file + README.
    </details>

  </details>  

  [Solution](https://github.com/Hunteena/wikipath)  


* **Graph Database Coding Challenge**  
  *Stack: Neo4j, Cypher, Jupyter Notebook, Flask.*
  
  <details><summary>Task Description</summary>  

  * Install a graph database from https://db-engines.com/en/ranking/graph+dbms  
     * Preferred: Neo4j, Nebula, ArangoDB
     * Preferred query language: Cypher  
  * Create a `.ipynb` notebook to:
    * Ingest data from source: https://disk.yandex.ru/d/s6wWqd8Ol_5IvQ
    * Import data from table into the graph database
    * Construct graph representation in the database, run queries in graph query language
    * Identify visual and algorithmic relationships (algorithms of your choice)
    * Build a Python REST service for the graph database that accepts a full name (input) and returns GraphML or JSON
    * Present results on GitHub with code + short presentation
    * Timeline: ~10 days.

  </details>  
  
  [Solution](https://github.com/Hunteena/neo4j)  

</details>


### Educational Projects at Netology

<details>

<summary>Expand</summary>

* **Programming Track**  

  * **Retail Chain Order Service API**  
    *Stack: Django/DRF, Pytest, Swagger, PostgreSQL, Celery, Docker, Git/GitHub.*  
    [Repository Link](https://github.com/Hunteena/python-final-diplom)  
    <details><summary>Details</summary>
    REST API (backend) for automating procurement in a retail chain with goods from multiple suppliers.
    </details>
  
  * **Classifieds Website API**  
    *Stack: Flask, SQLAlchemy, Celery, PostgreSQL, Docker, Git/GitHub.*  
    [Repository Link](https://github.com/Hunteena/hw_celery)  
    <details><summary>Details</summary>
    REST API (backend) for a classified ads website featuring user authentication and email newsletters.
    </details>
  
  * **Star Wars & Asyncio**  
    *Stack: Asyncio, SQLAlchemy, PostgreSQL, Git/GitHub.*  
    [Repository Link](https://github.com/Hunteena/hw_asyncio)  
    <details><summary>Details</summary>
    Asynchronous extraction of Star Wars characters from Star Wars API (SWAPI) and asynchronous loading into a PostgreSQL database.
    </details>
  
  
* **Analytics Track**  

  * **DWH (Data Warehouse) Capstone Project**  
    *Stack: SQL, PostgreSQL, DBeaver, Pentaho, Git/GitHub.*  
    [Repository Link](https://github.com/Hunteena/DWH_project), [Database Description](https://edu.postgrespro.ru/bookings.pdf)  
    <details><summary>Details</summary>
    Building dimension and fact tables based on a relational database.
    </details>
  
  * **"SQL and Data Retrieval" Module Project**  
    *Stack: SQL, PostgreSQL, DBeaver.*  
    [Database Description](https://drive.google.com/file/d/1-4Ue94fEosxeunO7tGl6KId7WvrB0rpc/view?usp=sharing), 
    [SQL Queries](https://drive.google.com/file/d/1eAVfYyq3DnraQNiNHgCP3r2D9-O8O6tc/view?usp=sharing)  
    <details><summary>Details</summary>
    Retrieving flight and airline data using advanced SQL queries (subqueries, CTEs / Common Table Expressions, materialized views).
    </details>

</details>

## Diplomas and Certifications

- **Python Developer from Scratch** (Curriculum [link](https://netology.ru/programs/python)), 
Professional Retraining Diploma <!-- ([link]()). -->  
_2022, Netology LLC_

- **Rest API (Intermediate) Certificate** ([link](https://www.hackerrank.com/certificates/a7b31380e4b7))  
_2022, HackerRank_  

- **ETL Developer** (Curriculum [link](https://netology.ru/programs/etl-developer)), 
Professional Development Certificate <!-- ([link](https://drive.google.com/file/d/143MDuKVVKvtsMMb3BpjRCVDtKbibAxMW/view?usp=sharing)). -->    
_2022, Netology LLC_  

- **SQL (Basic) Certificate** ([link](https://www.hackerrank.com/certificates/86b9fdaa561d))  
_2021, HackerRank_  

- **Learning How to Learn: Powerful mental tools to help you master tough subjects** (Curriculum [link](https://www.coursera.org/learn/learning-how-to-learn)), 
Certificate ([link](https://coursera.org/share/6ad6ccaa3354d6a5c77482103b825986))  
_2021, Coursera Inc, Deep Teaching Solutions_  

- **Machine Learning** (Curriculum [link](https://www.coursera.org/learn/machine-learning)), 
Certificate ([link](https://coursera.org/share/472683d93961060ca12f2666f6568306))  
_2018, Coursera Inc, Stanford University_


## Achievements

- Finalist in Yandex Programming Cup 2022 (Algorithms: Marathon)

## Contacts: 

- Email: nina.speranskaya35@gmail.com
- Telegram: [@Hunteena](https://t.me/Hunteena)
