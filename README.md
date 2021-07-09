# [Big Data Project (NLP and Recommendation System for beer)](https://github.com/FrankDTS/Big-data-Project)

  * Big data (2G) cleaning and data wrangling 
  * Built Recommendation System by built NLP
  * As a team leader, successfully assigned each member work content


# Data wrangling
 
 * First seperate data to three part, then deal with 1/3 part first.
 * Transform data to database format by first grouping 13 records together.
  
  ![](/images/1.pg)

 * based on [Kevin Jamieson's BeerMapper](https://homes.cs.washington.edu/~jamieson/BeerMapper.html), group 88 categories beer to 17 beer categories.
 * Group by profile name and grab overall scores’ min and max data which fulfill our conditions to make recommendation System.
 * Group 17 categories into 5 styles by creating our own conditiona.

# Built NLP model
 
 * Used String and str package to remove stop words and punctuation, then transfome text data to lower case. 
 * Tf-idf and XGboost classfier with gridsearch
 
