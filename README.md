# Recommendations  with IBM project


> ### Introduction :

In this project we'll analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they'll like.

> ### Motivation

For this project I will be looking at the interactions that users have with articles on the IBM Watson Studio platform. Below It can be seen an example of what the dashboard could look like displaying articles on the IBM Platform.

![Alt text](https://github.com/AnwarJamal16/Articles-Recommendation/blob/master/img/Recommendations_with_IBM.png)

The above dashboard is just showing the newest articles. It could imagine having a recommendation board available here that shows the articles that are most pertinent to a specific user.


> ### Libraries :
	
* pandas
	
* numpy
	
* matplotlib
	
* pickle
	
* re
	
* nltk
	
* sklearn
	
> ### Data :

* user-item-interactions.csv: Interactions between users and articles.

* articles_community.csv: Contents of articles.

> ### Files :

* Recommendations_with_IBM.html : This is the html screenshot of the jupyter notebook 'Recommendations_with_IBM' and contains all the code with its output.
    
* Recommendations_with_IBM.ipynb : The jupyter notebook where all the coding has been done.

* project_tests.py : Some tests written by udacity to check the answers to the questions in Recommendation_with_IBM.ipynb.

* top_10.p, top_20.p, top_5.p : Python pickle files for tests used in the notebook.

* user_item_matrix.p : Python pickle file providing data used in making the recommendation model.


> ### Overview :

#### I. Exploratory Data Analysis

Before making recommendations of any kind, you will need to explore the data you are working with for the project. Dive in to see what you can find. There are some basic, required questions to be answered about the data you are working with throughout the rest of the notebook. Use this space to explore, before you dive into the details of your recommendation system in the later sections.

#### II. Rank Based Recommendations

To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

#### III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users

#### IV. Content Based Recommendations

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

#### V. Matrix Factorization

Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, you will build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an individual might interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.
Reference


> ### Acknowledgement:

* Udacity For great course materials

* IBM For the dataset
