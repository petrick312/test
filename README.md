# We-R-No-Angels<br>
## City of Angels analysing Los Angeles crime data<br>

<strong>Participants:</strong> Haritha Koleti, Michelle Petras, Veethika Singh, Kathleen Snider-Belinski, Carmen Wiggins<br><br>

Data was downloaded from the City of Los Angeles at this URL: https://data.lacity.org/Public-Safety/CrimeData-from-2020-to-Present/2nrs-mtv8/about_data.<br>
The data contains crime information accumulated from 2020 through the first few months of 2024<br>
The goal of this analysis is to identify patterns, trends, and factors contributing to crime in LA to predict hotspots and understand the factors that influence crime rates.  <br>

<strong>Tools Used</strong>
  - Python
  - Pandas
  - Numpy
  - Jupyter Notebook
  - Matplotlib
  - Plotly Dahs
  - Leaflet
  - Machine Learning
  - SCKit
  - Spark SQL
  - Tableau
  - Heroku
  
<strong>Challenges and Solutions</strong>
  - Plotly Dash with Spark: Spark had issues with Plotly Dash, so we implemented Plotly with Pandas DataFrames.
  - Heroku: We chose Heroku for app deployment, but it required a purchase.
  - Tableau: Tableau occasionally deleted our work, causing setbacks.

<strong>Machine Learning Approach</strong><br>
We performed data cleaning, tuning, and binning by crime type to prepare the data. The results of our machine learning models were as follows:
  - Logistic Regression: Achieved 19% accuracy with all features included.
  - Random Forest: Achieved 35% accuracy which was closer.  
  - Focused Feature Analysis: By focusing on specific features like area, gender, and age, we achieved 89% accuracy. We also explored interesting outliers using these methods, even with lower accuracy scores.
  - Model Comparison: Random Forest provided the highest or equal scores compared to other models.

<strong>Files and Work Process</strong><br>
<strong>Work process:</strong> Filename<br>
<strong>Machine learning:</strong> Crime_analysisRF_tune.ipynb<br>
<strong>Spark, Dash:</strong>  Crime_data_imp_dash.ipynb<br>
<strong>Outliers:</strong> Outliers.ipynb<br>
<strong>Crime Bins:</strong> Crime_bins.csv<br>

### Links

<strong>GitHub Repository</story><br>
Files are located in https://github.com/haritha3679/We-R-No-Angels<br>

<strong>Tableau</strong><br>
  - https://public.tableau.com/app/profile/carmen.wiggins/viz/DashboardProject4_17193531816340/Dashboard1<br>
![tableau](https://github.com/haritha3679/We-R-No-Angels/blob/main/static/img/tableu.png?raw=true)

<br><strong>Crime Map</strong><br>
  - https://github.com/petrick312/la_crime_map<br>
![map](https://github.com/haritha3679/We-R-No-Angels/blob/main/static/img/map.png?raw=true)


![models](https://github.com/haritha3679/We-R-No-Angels/blob/main/static/img/ML_Model_comp.png?raw=true)
