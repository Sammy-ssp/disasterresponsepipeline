# Disaster Response Pipeline Project


### Table of Contents

1. [Project Motivation](#motivation)
2. [Requirements](#requirements)
3. [Files in the Repository](#filesintherepository)
4. [Results](#results)
5. [Acknowledgements](#acknowledgements)


## Project Motivation <a name="motivation"></a>

As part of the Data Science Nanodegree Program by Udacity in collaboration with Figure Eight, the aim of this project is to develop a classification model based on Natural Language Processing (NLP) to analyze messages and identify distinct needs after a disaster.

The project is divided in the following parts:
    1. ETL Pipeline, Data processing, cleaning
    2. Save cleaned dataset in a database
    3. Build machine learning pipeline to train a model to classify text messages into categories
    4. Deploy web app to show model results

## Requirements <a name="requirements"></a>

The project should run with libraries included in the Anaconda distribution. Following main libraries have been used:

  - Python 3.8.2
  - numpy 1.13.3
  - pandas 0.25.3
  - matplotlib 0.8.4
  - seaborn 0.10.0
  - scikit-learn 0.24.2
  - nltk 3.6.2


## Files in the Repository <a name="filesintherepository"></a>

App folder contains the following:
- templates: Folder containing
    - master.html: Renders homepage
    - go.html: Renders the message classifier
- run.py: Defines the app routes

Data folder contains the following:
- disaster_categories.csv: contains the disaster categories csv file
- disaster_messages.csv: contains the disaster messages csv file
- DisasterResponse.db: contains the emergency db (merge of categories and messages by ID)
- process_data.py: contains the scripts to transform data

Models folder contains the following:
- classifier.pkl: contains the RandomForestClassifier pickle file
- train_classifier.py: script to train pipeline

## Results <a name="results"></a>

The results are published in the web app.

## Acknowledgements <a name="acknowledgements"></a>

The data for the project is provided from Figue Eight.
Thanks to Udacity for a great project.



