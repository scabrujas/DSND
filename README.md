
# Disaster Response Pipelines

## Project Motivation

Build an application to classify and show insights on disaster message data provided by Figure Eight,using NLP and data engineering to create and train a machine learning model.

## Structure :
        .
        ├── app     
        │   ├── run.py                                # Flask file that runs app
        │   └── templates   
        │       ├── go.html                           # Classification result page of web app
        │       └── master.html                       # Main page of web app    
        ├── data                   
        │   ├── disaster_categories.csv               # Dataset including all the categories  
        │   ├── disaster_messages.csv                 # Dataset including all the messages
        │   ├── ETL Pipeline Preparation.ipynb        # ETL process preparation
        │   └── process_data.py                       # Data cleaning
        │   
        ├── models
        │   ├── ML Pipeline Preparation.ipynb         # Machine Learning model preparation
        │   └── train_classifier.py                   # Train ML model           
        └── README.md

## Instructions:
1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python app/run.py`

3. Go to http://0.0.0.0:3001/

## Libraries used:
- Pandas
- Numpy
- Scikit-learn
- Plotly
- Flask
- Plotly
- sqlalchemy

