# SQL-Analysis-of-California-Traffic-Collisions

## Project overview
Exploratory data analysis using sql in jupyter notebook with the aid of jupysql (an improvement over ipythonsql) and duckdb (which is an in-process SQL OLAP Database Management System). The database used is the California Traffic Collision Data from SWITRS obtained from [kaggle](https://www.kaggle.com/datasets/alexgude/california-traffic-collision-data-from-switrs?resource=download).

### Database overview
There are three main tables:
1. collisions: Contains information about the collision, where it happened, what vehicles were involved etc. ,each row represents a distinct collision.
2. parties contains information about the groups of people directly involved in the collision.
3. victims contains information about the injuries of specific people involved in the collision.

### Some insights from the analysis
1. The database contained records of collisions from 1st of january, 2001 to 3rd of june, 2021
2. The year 2002 had the highest collisions recorded. The top 3 years with highest collsions records are 2002, 2003,2004.
3.  Los angeles has the highest collisions with more than 2M entries while sierra has the lowest with about 1447 collisions recorded
4.  Overall, 73007 died due to traffic collisions, while more than 5 million people sustained various forms of injury
5.  The number one PCF (Primary Collision Factor) Violation Category is speeding
6.  About 16.51% of the overall traffic collisions happened on Friday,followed by thursdays with 14.77% while sunday has the lowest collision and accounts for about 11.7% of overall traffic collisions
7. With respect to the parties directly involved in collisions, males make up about 61.27% of the total people involved while females and non binary make up 38.7% and 0.02% respectively
8. Whites make up the larger proportion of parties involved in traffic collisions
9. About 52448 collisions involved school buses, and this accounts for about 0.56% of total collisions.
10. There are more victims within the age groups of 10-20 and 20-30, than any other age groups

## Conclusion
There is so much to discover from analysing this database. I have attempted to answer just some few questions in this notebook but further analysis can always be carried out to discover more interesting information.
