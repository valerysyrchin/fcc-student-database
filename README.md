# FreeCodeCamp: Student Database

[Русское описание ниже](#описание-проекта-на-русском)

An educational project created as part of the freeCodeCamp "Relational Database" course. In this workshop, a complete relational database for students, courses, and majors was designed, implemented, and populated.

### Tech Stack
* **Database:** PostgreSQL
* **Query Language:** SQL
* **Automation:** Bash (used for data parsing and automatic import)

### Key Achievements & Skills Learned:
* Designed a relational database schema from scratch.
* Configured primary keys (`PRIMARY KEY`) and foreign keys (`FOREIGN KEY`) to establish table relationships.
* Developed automation Bash scripts to read and process external data files.
* Utilized Bash loops and the `psql` CLI utility to dynamically import data from CSV files directly into the database.
* Handled comma-separated string parsing and safely inserted records into SQL tables using `INSERT INTO` queries.
* Worked interactively within the PostgreSQL terminal to verify database states and test results.

### Project Structure
* `students.sql` — database schema script containing the complete table structures.
* `insert_data.sh` — Bash script that automatically parses `students.csv` / `courses.csv` and populates the database.
* `students.csv` / `courses.csv` — raw data source files used for the import.

---

## Описание проекта на русском

Учебный проект, созданный в рамках воркшопа от freeCodeCamp по курсу Relational Database. В ходе выполнения этого проекта была спроектирована и создана база данных студентов, курсов и их оценок.

### Технологический стек
* **СУБД:** PostgreSQL
* **Язык запросов:** SQL
* **Автоматизация:** Bash (использовался для импорта и парсинга данных)

### Чему я научился в этой части:
* Проектировать схему реляционной базы данных с нуля.
* Настраивать первичные (`PRIMARY KEY`) и внешние ключи (`FOREIGN KEY`) для связывания таблиц.
* Писать автоматизационные Bash-скрипты для чтения и обработки внешних данных.
* Использовать циклы в Bash и утилиту `psql` для динамического импорта данных из CSV-файлов (`students.csv`, `courses.csv`) прямо в базу данных.
* Обрабатывать строки, разделенные запятыми, и корректно вставлять их в SQL-таблицы с помощью конструкции `INSERT INTO`.
* Использовать терминал PostgreSQL для интерактивной работы и проверки результатов.

### Структура проекта
* `students.sql` — готовый скрипт со всей структурой (схемой) базы данных.
* `insert_data.sh` — Bash-скрипт, который автоматически считывает файлы `students.csv` и `courses.csv` и наполняет базу данных актуальной информацией.
* `students.csv` / `courses.csv` — исходные файлы с данными студентов и курсов.
