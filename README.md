# Lab 08 – Database Functions and Triggers


## Tasks

In our database, there is a table called airports_data that contains a column called coordinates. The goal is to convert these coordinates into real address.
To achieve this, the following steps need to be taken:
Create a function that retrieves all addresses where both coordinates are not less than 35 and not greater than 50.
Call this function from a Python script and use geoPy to obtain address from the coordinates.
Your python script should create a new table called Address with the following columns: address_id, address_text, address_x, address_y..

[Postgresql Functions](https://www.postgresqltutorial.com/postgresql-python/postgresql-python-call-postgresql-functions/)

[Python Script](https://github.com/enghamzasalem/Create_db_faker)

[geoPy](https://pypi.org/project/geopy/)

* Task:  Coordinates → Address (Python + PostgreSQL)

## Submission Instructions

1. Create a new branch:

   ```
   git checkout -b yourname_lab08
   ```

2. Complete all tasks.

3. Commit your work:

   ```
   git add .
   git commit -m "Lab08 submission - Your Name"
   ```

4. Push your branch:

   ```
   git push origin yourname_lab08
   ```

## Requirements
* Do NOT push to the main branch
* SQL files must run without errors
* Python script must execute successfully
* Use LIMIT to avoid API rate limits

## Deadline

03-19-2026
