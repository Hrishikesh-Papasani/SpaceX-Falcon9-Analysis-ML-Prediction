# Falcon 9 Analytics: Exploring SpaceX's Journey

- Data collection from REST API's and Wikipedia (web-scraping)
- Exploratory data analysis performed utilizing fundamental python libraries for Data exploration, Data manipulation, Data cleaning and visualisation
- Folium is used to create illustrative maps for further insights
- Plotly Dash visualisation tools used to construct a comprehensive Dashboard 
- Predictive Machine learning model development (With Hyperparameter tuning and Cross validation)

<p align="center">
  <img width="600" alt="image" src="https://github.com/Hrishikesh-Papasani/SpaceX-Falcon9-Analysis-ML-Prediction/assets/128984594/6ae79a95-5ac3-463d-8712-dc24ca9d506c">
</p>


## Project report 

Refer [final_project.pdf](final_project.pdf) document

Outline:
- Executive Summary
- Introduction
- Methodology
- Results
- Conclusion
- Appendix


## Repository structure:

#### [API-data-collection.ipynb](API-data-%20collection.ipynb)
- This notebook extracts data regarding Falcon 9 launches from REST API's. 
- [dataset_part_1.csv](dataset_part_1.csv) CSV file is produced as the outcome.


#### [webscraping.ipynb](webscraping.ipynb)
- This notebook is used for scraping data of Falcon 9 launches from Wikipedia. 
- [spacex_web_scraped.csv](spacex_web_scraped.csv) CSV file is produced as the outcome.


#### [EDA(Base).ipynb](EDA(base).ipynb)
- We perform base data exploration and data cleaning in this notebook.
- [dataset_part_2.csv](dataset_part_2.csv) CSV file is produced as the outcome.

#### [EDA(SQL).ipynb](EDA(SQL).ipynb)
- We further explore data and insights through SQL.
- 'my_date1.db' (Engine for enabling the execution of SQL queries on the dataset).
- [Spacex.csv](Spacex.csv) file is used.

#### [EDA(DV).ipynb](EDA(DV).ipynb)
- We explore insights through data visualisation using Matplotlib and Seaborn.
- Feature engineering is performed.
- [dataset_part_3.csv](dataset_part_3.csv) as the outcome.

#### [folium-maps.ipynb](folium-maps.ipynb)
- Launch Sites Locations Analysis with Folium.
- Refer [Folium Maps](Folium%20Maps%20(pictures)) folder for screenshots (If not directly shown in the notebook).

#### [dashboard.py](dashboard.py)
- Dashboard creation using Plotly Dash.
- Refer [Dashboard (pictures)](Dashboard%20(pictures)) for screenshots.


#### [ML-model-building.ipynb](ML-model-building.ipynb)
- Machine learning model building (4 major classification models)
- Data scaling, feature engineering, model building, hyperparameter tuning, model evaluation.



Note: Outputs may not directly be shown in the Folium and Plotly Dash files. Refer their respective picture folders for reference.

This project was developed as part of the IBM's Applied Data Science Capstone. However, different changes/improvements have been made to further optimise the project.




