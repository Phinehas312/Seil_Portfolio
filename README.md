# Seil_Portfolio
Data science projects overview

# [Project 1: COVID-19 Research Articles Analysis and Visualization](https://github.com/Phinehas312/COVID19_Research_Articles_Analysis_and_Visualization/tree/main/CORD19)
* Created a COVID-19 Research Articles Dataset Browser, a dashboard system with an automated pipeline that summarizes COVID-19 research articles by incorporating three techniques: clustering, citation networks, and Q&A system.
* The production of vast amounts of Covid-19 research publications has made it harder for users to look for publications, and also hinders the process of exploring them.
* COVID-19 Open Research Dataset (CORD-19) is a text dataset of over 200,000 research articles’ abstracts, body texts, and metadata downloaded from National Institutes of Health. We sampled 10,000 articles for our project.
* Document clustering: We represented documents using TF-IDF, reduced dimensionality using PCA and t-SNE, and clustered documents with k-means and LDA.
* Graph analysis: We created a citation network between the articles using NetworkX and ArgoLite. For analyzing the influential capacity of each papers, we focused on in-degree and VoteRank centrality metrics.
* Question Answering: We used a deep-learning model from HuggingFace library which utilizes BERT model for automated question answering.
* Comparing with LDA, k-means produced 20 different topics of cluster assignments with less overlap.
* Overwhelming number of articles referenced one paper 156 times, and VoteRank was more efficient in determining influential papers, compared to degree centrality.

![](https://github.com/Phinehas312/Seil_Portfolio/blob/main/images/doc_clustering.png)
![](https://github.com/Phinehas312/Seil_Portfolio/blob/main/images/citation_graph.png)

# [Project 2: Establishing a Georgia Tech COVID-19 Testing System Database](https://github.com/Phinehas312/GT_COVID19_TestingSystemDB)
* Analyzed and designed the entity relationship diagram, specified relational schema, and implemented procedures of online Georgia Tech COVID-19 testing system database.
* Used the classical methodology for relational database development and implemented the system using a relational DBMS that supports standard SQL series.
* Used my localhost MySQL Server to implement my database and the application.
* Phase 1: Translated the entire description of the system into an entity-relationship diagram(ERD) for a potential database sytem.
* Phase 2: Translated the ERD into a relational schema diagram, and then translated ERD into create table & insert statements.
* Phase 3: Implemented a list of stored procedures for the GT COVID-19 Testing System.

![](https://github.com/Phinehas312/Seil_Portfolio/blob/main/images/Phase%201%20ERD.jpg)

# [Project 3: Optimizing a Diet Using PuLP](https://github.com/Phinehas312/Optimizing_diet)
* Found a way to satisfy the nutritional requirements of soldiers back in 1930's and 40's, while minimizing the cost.
* Formulated an optimization model(a linear program) to find the cheapest diet that satisfies the maximum and minimum daily nutrition constraints, and solved it using PuLP.
* For the first part, I made the model by only setting up the minimum and maximum constraints for each nutrition.
* For the second part, I added the following constraints to make the model: Many people dislike celery and frozen broccoli, so at most one was chosen. To get day-to-day variety in protein, at least 3 kinds of meat/poultry/fish/eggs were selected.
* As a result, the optimal amount was $4.34 for the first part, and $4.51 for the second part.
* The second result was almost the same as the first but slightly higher, from which we can assume that more constraints actually had some effects in the model, leading to a higher cost.
