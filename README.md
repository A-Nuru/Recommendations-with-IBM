# Recommendations-with-IBM

## Contents
1. [Installation](https://github.com/A-Nuru/Recommendations-with-IBM#Installation)
2. [Introduction](https://github.com/A-Nuru/Recommendations-with-IBM#Introduction)
3. [Instructions](https://github.com/A-Nuru/Recommendations-with-IBM#Instructions)
4. [Results](https://github.com/A-Nuru/Recommendations-with-IBM#Results)
5. [Licensing](https://github.com/A-Nuru/Recommendations-with-IBM#Licensing)

## Installation
No libraries is needed to run the code than the Anaconda distribution of Python. 
The code should run with no issues using Python versions 3.


## Introduction
In this adventure, I analyzed the interactions that users have with articles on the IBM Watson Studio platform, 
and make recommendations to them about new articles you think they will like. Below you can see an example of what 
the dashboard could look like displaying articles on the IBM Watson Platform.


Though the above dashboard is just showing the newest articles, you could imagine having a recommendation board available here
that shows the articles that are most pertinent to a specific user.

## Instructions
In order to determine which articles to show to each user, I performed a study of the data available on the IBM
Watson Studio platform. You can also create your own account to become a part of their community, and get a better understanding 
of their data by creating an account if you have interest in this work.

I The project was divided into the following tasks

I. Exploratory Data Analysis

Before I dive into the details of the recommendation system in the later sections, I explored the data to see what I can find. 
There were some basic, required questions I answered about the data while working through the notebook.

II. Rank Based Recommendations

To get started in building recommendations, you will first find the most popular articles simply based on the most interactions. 
Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular.
These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms 
of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in 
the right direction towards more personal recommendations for the users. You will implement this next.

IV. Content Based Recommendations (EXTRA - NOT REQUIRED)

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

V. Matrix Factorization

Finally, you will complete a machine learning approach to building recommendations. Using the user-item interactions, you will
build out a matrix decomposition. Using your decomposition, you will get an idea of how well you can predict new articles an 
individual might interact with (spoiler alert - it isn't great). You will finally discuss which methods you might use moving forward,
and how you might test how well your recommendations are working for engaging users.

## Results
Check the codes and outcomes [here.](https://github.com/A-Nuru/Recommendations-with-IBM/blob/master/Recommendations_with_IBM.ipynb)

## Licensing, Authors, Acknowledgements
You can find the Licensing [here](https://github.com/A-Nuru/Recommendations-with-IBM/blob/master/LICENSE.txt). Otherwise, feel free to use the code here as you would like!

