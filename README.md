## Packages required:
1. scikit-learn
2. scipy.stats
3. Pandas
4. Streamlit
4. Numpy

## Datasets
USA Real Estate
https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset

## Running Demo App

streamlit run Path\To\Repository\real_estate_analysis\demo_app.py

## Running re_retirement_ank.py
This Python script is used for preprocessing the data and compute senior suitability score for the properties in our datasets
It outputs the transformed dataset to Suitability_score_house.csv

### To Run:
python re_retirement_rank.py

it may take a few hours for the program to process the data.

Note that demo_app.py, demo_web_interface.py and recommender_knn.py require Suitability_score_house.csv to work, as that file has the data used to train the ML models.

## Running the demo Web Interface
enter the following command:

streamlit run Path\To\Repo\Real_Estate_Analysis\demo_web_interface.py

## Running recommender_knn.py
python Path\To\Repo\Real_Estate_Analysis\recommender_knn.py

