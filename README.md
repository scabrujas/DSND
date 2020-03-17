
# How to succeed in Airbnb Boston's market

## Project Motivation
Use the Cross-Industry Standard Process of Data Mining (CRISP-DM) and the Boston Airbnb datasets to estimate the price, know which factors impact the most on it and get to know better the users.

## Business Understanding
From the dataset is possible to know what are the preference of the users when they are staying in Boston. We will try to answer this questions using the dataset:

- What do the users look for in an Airbnb?
- What impacts the prices negatively?
- What room type gets better reviews?

## Data Understanding
Boston Airbnb dataset consists of 3585 rows and 95 columns, each row is a listing

## Process the Data
The columns were cleaned, the NAN values filled with the mean and the median according to the needs and the qualitative data processed, more details in the Preprocessing section

## Data Modeling
Using the Linear Regression model on the processed data, and getting the coefficients of every feature we can know the relevance of each feature, more details in the Result section

## Results and discussion:
Published in https://medium.com/@scabrujas/how-to-succeed-in-airbnb-bostons-market-7807a116d6f5

## File Description
Jupyter Notebook with the data analysis and the ML model (Project1.ipynb)
Boston Airbnb data (listings.csv): http://insideairbnb.com/get-the-data.html

## Libraries used:
- Pandas
- Numpy
- Scikit-learn
- Seaborn
- Matplot

## Conclusions
- We preprocessed the Boston Airbnb data,taking care of missing values and qualitative variables.
- We created a Machine Learning model to estimate the Airbnb prices in Boston.
- We establish what features impacts in the price rather in a possitive or a negative way.
- We took a look on the reviews per room type, wranglin the data and using visualization to drive the analysis.
