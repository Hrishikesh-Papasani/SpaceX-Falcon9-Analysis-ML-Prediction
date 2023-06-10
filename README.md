# SpaceX-Falcon-Analysis-ML-Predictions

- Data collection from REST API's and Wikipedia (web-scraping)
- Exploratory data analysis performed utilizing fundamental python libraries for Data exploration, Data manipulation, Data cleaning and visualisation

- Folium is used to create illustrative maps for further insights
- Plotly Dash visualisation tools used to construct a comprehensive Dashboard 
- Predictive Machine learning model development (With Hyperparameter tuning and Cross validation)

## Project report (refer 'final_project.pptx' document)

Outline:
- Executive Summary
- Introduction
- Methodology
- Results
- Conclusion
- Appendix


## Repository structure:

#### 'API-data-collection.ipynb'
- This notebook extracts data regarding Falcon 9 launches from REST API's provided. 
- 'dataset_part_1.csv' CSV file is produced as the outcome.


#### 'webscraping.ipynb'
- This notebook is used for scraping data regarding Falcon 9 launches from Wikipedia. 
- 'spacex_web_scraped.csv' CSV file is produced as the outcome.


#### 'EDA(Base).ipynb'
- We perform basic data exploration and data cleaning in this notebook.
- 'dataset_part_2.csv' CSV file is produced as the outcome.

#### 'EDA(SQL).ipynb'
- We further explore data and insights through SQL.
- 'my_date1.db' (Engine for enabling the execution of SQL queries on the dataset).
- 'Spacex.csv' file is used.

#### 'EDA(DV).ipynb'
- We explore insights through data visualisation using Matplotlib and Seaborn.
- 'dataset_part_3.csv' is produced as the outcome.

#### 'folium-maps.ipynb'
- Launch Sites Locations Analysis with Folium.
- Refer 'Folium Maps (pictures)' folder for screenshots (If not directly shown in the notebook).

#### 'dashboard.py'
- Dashboard creation with Plotly Dash.
- Refer 'Dashboard (pictures)' for screenshots.


#### 'ML-model-building.ipynb'
- Machine learning model building (4 classification models)
- Data scaling, feature engineering, model building, hyperparameter tuning, evaluation



