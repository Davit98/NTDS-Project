# A Culinary Tour of Data Science
Exploring the Epicurious recipe data available on [Kaggle](https://www.kaggle.com/hugodarwood/epirecipes#full_format_recipes.json) using network science and graph theory.

#### Prerequisites

* nltk 3.4.5
* networkx 2.3
* numpy 1.16.5
* pandas 0.25.1
* seaborn 0.9.0


#### File descriptions

_Data Processing and Graph Construction.ipynb_ - uses natural language processing techniques to extract ingredients from a raw recipe text for each dish and then builds a weighted graph with nodes being dishes and connects them based on the common ingredients they share using Jaccard simialrity index

_Exploring the Graph.ipynb_ - explores the structure and various properties of the graph

_Data Exploitation.ipynb_ - this is the main notebook which tries to answer the research questions. It includes the following:

* Network visualizations
* Clustering using Louvain method (community detection)
* KNN-based recommender system
* Logistic regression model predicting recipe ratings using graph filtering
