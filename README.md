# ftde2-Project_1 (Batch Processing)

This project demonstrates a simple ETL (Extract, Transform, Load) process and outputs a dashboard for visualizing the processed data. The ETL pipeline extracts data, performs necessary transformations, and loads the cleaned data into a PostgreSQL database. The final output is a dashboard that provides insights and visual representations of the data into Google Data Studio.


## Background Project
The data analyst team requires a table to create a dashboard detailing orders from the data stored in the production database marketplace. As the data engineer, your task is to develop a data migration script that transfers the necessary tables from the production database to the data warehouse. This ensures that the data analyst team can use the table from the data warehouse without placing a burden on the production database marketplace.

The data analyst team has provided the required schema, outlining the columns needed for their analysis.
```sql
order_id INT NOT NULL,
order_date DATE NOT NULL,
user_id INT NOT NULL,
payment_name VARCHAR(255),
shipper_name VARCHAR(255),
order_price INT,
order_discount INT,
voucher_name VARCHAR(255),
voucher_price INT,
order_total INT,
rating_status VARCHAR(255)
```


## Requirements
This project requires the following:
* psycopg2-binary: A PostgreSQL adapter for Python to connect and interact with PostgreSQL databases.
* SQLAlchemy: An SQL toolkit and Object-Relational Mapping (ORM) library for Python, used to manage database connections and queries.
* sqlparse: A non-validating SQL parser for Python, used for parsing SQL queries.
* pandas: A powerful data manipulation and analysis library for Python, used for data transformation and analysis in the ETL process.

```python
Python 3.10
psycopg2-binary ==2.9.3
SQLAlchemy ==1.4.40
sqlparse ==0.4.2
pandas ==1.4.3
```
## Output
[Dashboard](https://lookerstudio.google.com/reporting/4e4c57a4-12fa-45c2-9d5f-769e0b562520)
![image](https://github.com/user-attachments/assets/7eacd1df-c028-433d-8e8d-509c57e43571)

## Additional
NBT stands for Newbie Team. We're a group project for the fast-track data engineering batch 2 at Digital Skola. The team consists of:
* Gusti Imam S.
* Muhammad Ramadhani
* Nindya Nova P.S
* Suyanto
* Wisnu Setya



