Case Study: Regression


Scenario

You are working as an analyst for a real estate company. Your company wants to build a machine learning model to predict the selling prices of houses based on a variety of features on which the value of the house is evaluated.
Objective
Your job is to build a model that will predict the price of a house based on features provided in the dataset. Senior management also wants to explore the characteristics of the houses using some business intelligence tools. One of those parameters includes understanding which factors are responsible for higher property value - $650K and above.
Dataset

The dataset consists of information on 22,000 properties. The dataset consists of historic data of houses sold between May 2014 to May 2015.
These are the definitions of data points provided:
Note: For some of the variables are self-explanatory, no definition has been provided.

Id: Unique identification number for the property
date: the date the house was sold
price: the price of the house
waterfront: the house which has a view to a waterfront
condition: How good the condition is (Overall). 1 indicates worn-out property and 5 excellent.
grade: Overall grade given to the housing unit, based on the King County grading system. 1 poor, 13 excellent.
Sqft_above: square footage of house apart from the basement
Sqft_living15: Living room area in 2015(implies-- some renovations) This might or might not have affected the lotSize area.
Sqft_lot15: lotSize area in 2015(implies-- some renovations)
Expected Outcomes

We encourage you to thoroughly understand your data and take the necessary steps to prepare your data for modeling before building exploratory or predictive models.
Since this is a classification model, you can use linear regression for classification for building a model. You are also encouraged to use other models in your project including KNN, decision trees for regression.

1. Explore the data

To explore the data, you can use the techniques that have been discussed in class. Some of them include using the describe method, checking null values, using Matplotlib, and Seaborn for developing visualizations.
The data has many categorical and numerical variables. Explore the nature of data for these variables before you start with the data cleaning process and then data pre-processing (scaling numerical variables and encoding categorical variables).

2. Build a Model

Use different models to compare the accuracies and find the model that best fits your data. You can use the measures of accuracies that have been discussed in class. Please note that while comparing different models, make sure you use the same measure of accuracy as a benchmark.

3. Visualize

You will use Tableau to visually explore the data further. The questions have been provided in this document for which you can use tableau.

Deliverables

A slides deck: use slides.com for simple yet effective templates or download the templates inside this repo.
A presentation: Your public presentation should last between 5 and 7 minutes.
SQL Queries: Access SQL Questions Doc and make sure you run these queries using SQL.
A Tableau Dashboard: Follow the instructions in this document to build in Tableau.
Python code: Your code will be reviewed. Make sure you follow the best practices explained in the class so far.

Evaluation Criteria

Critical Thinking
Communication
Transparency
Thoroughness


Tips & Tricks

Organize yourself (don’t get lost!). Respect deadlines.
Ask for help but don’t forget that Google is your friend.
Define a simple approach first. You never know how the data can betray you. :wink:
Document your work.
Learn about the problem and what research has been done before you.
Before making a graph, think about what you want to represent.
