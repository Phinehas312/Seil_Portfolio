# Seil_Portfolio
Example data science portfolio

# [Project 1: Establishing a Georgia Tech COVID-19 Testing System Database](https://github.com/Phinehas312/GT_COVID19_TestingSystemDB)
* Analyzed and designed the entity relationship diagram, specified relational schema, and implemented procedures of online Georgia Tech COVID-19 testing system database.
* Used the classical methodology for relational database development and implemented the system using a relational DBMS that supports standard SQL series.
* Used my localhost MySQL Server to implement my database and the application.

![](https://github.com/Phinehas312/Seil_Portfolio/blob/main/images/Phase%201%20ERD.jpg)

# [Project 2: Optimizing a Diet Using PuLP](https://github.com/Phinehas312/Optimizing_diet)
* Found a way to satisfy the nutritional requirements of soldiers back in 1930's and 40's, while minimizing the cost.
* Formulated an optimization model(a linear program) to find the cheapest diet that satisfies the maximum and minimum daily nutrition constraints, and solved it using PuLP.
* For the first part, I made the model by only setting up the minimum and maximum constraints for each nutrition.
* For the second part, I added the following constraints to make the model: Many people dislike celery and frozen broccoli, so at most one was chosen. To get day-to-day variety in protein, at least 3 kinds of meat/poultry/fish/eggs were selected.
* As a result, the optimal amount was $4.34 for the first part, and $4.51 for the second part.
* The second result was almost the same as the first but slightly higher, from which we can assume that more constraints actually had some effects in the model, leading to a higher cost.
