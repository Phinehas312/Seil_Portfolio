# Seil_Portfolio
Example data science portfolio

# [Project 1: Optimizing a Diet Using PuLP] (https://github.com/Phinehas312/Seil_Portfolio/blob/main/Project_Optimizing%20a%20Diet%20Using%20PuLP.ipynb)
* Found a way to satisfy the nutritional requirements of soldiers back in 1930's and 40's, while minimizing the cost.
* Formulated an optimization model(a linear program) to find the cheapest diet that satisfies the maximum and minimum daily nutrition constraints, and solved it using PuLP.
* For the first part, I made the model by only setting up the minimum and maximum constraints for each nutrition.
* For the second part, I added the following constraints to make the model: Many people dislike celery and frozen broccoli, so at most one was chosen. To get day-to-day variety in protein, at least 3 kinds of meat/poultry/fish/eggs were selected.
* As a result, the optimal amount was $4.34 for the first part, and $4.51 for the second part.
* The result was almost the same but slightly higher, from which we can assume that more constraints actually had some effects in the model, leading to a higher cost.
