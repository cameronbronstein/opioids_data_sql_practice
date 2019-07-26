# PostgreSQL and PsycoPG2 - SF Flex Lesson
**Author**: Cameron Bronstein

This is an intermediate introduction to SQL querying language using the `psycopg2` python wrapper/ API.

**The goals of this lesson are:** 
- To gain experience querying a database with SQL
- Understanding relational database structure/ why to store data in different tables
- Understanding how to query data from multiple tables
- Understanding use cases for Pandas vs. other more efficient methods (Data Science vs. Data Engineering)
- Think about how databases are used in the structure of most web pages.
- Think about some PostgreSQL command line tools for structure data in an efficient way.

#### Dependencies
- `psycopg2`: [version 2.7.7](http://initd.org/psycopg/docs/install.html#binary-install-from-pypi)
- `postgreSQL`: [version 11.x](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)

## Data
The data comes from the DEA and [Washington Post](https://www.washingtonpost.com/graphics/2019/investigations/dea-pain-pill-database/?utm_term=.975ecc525b4b).

Data was cleaned and cut down for the purposes of this lesson. The cleaned data can be downloaded from [Google drive](https://drive.google.com/file/d/1PfOe6ERFgo1tJi_MkVePiJ2lOyBPON0c/view?usp=sharing), or the raw data can be passed through the **data cleaning** notebook.

