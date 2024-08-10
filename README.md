# Flight Fare Prediction: [[WebApp Link]](https://lukechugh-flight-fare-prediction-webapp.up.railway.app/)

![](https://img.shields.io/badge/python-3.7-blueviolet)
![](https://img.shields.io/badge/scikit--learn-0.24.1-blue)
![](https://img.shields.io/badge/Frontend-HTML/CSS-fuchsia)
![](https://img.shields.io/badge/flask-2.1.2-aquamarine)

Input Departure Date, Arrival Date, Starting Point, Ending Destination, Number of Stops and the Name of the Airlines and this WebApp will predict the price of your flight using Random Forests
<p style="text-indent: 20px;">
♦ Dataset was obtained by web-scraping records from "Ease My Trip" website using beautiful soup
</p>
<p style="text-indent: 20px;">
♦ Checked for null values and imputed them with appropriate techniques
</p>
<p style="text-indent: 20px;">
♦ Extracted year, month, day, hour and minutes from "Date of Journey", "Departure Time" and "Arrival Time" using pandas 
</p>
<p style="text-indent: 20px;">
♦ Handled categorical data using OneHotEncoder and LabelEncoder
</p>
<p style="text-indent: 20px;">
♦ Implemented Exploratory Data Analysis
</p>
<p style="text-indent: 20px;">
♦ Implemented pre-model feature selection and visualized the most important features using heatmap and SelectKBest. Implemented post model feature selection using ExtraTreesRegressor
</p>
<p style="text-indent: 20px;">
♦ Used LazyPredict library to build a report of adjusted R square scores of 10 models sorted in descending order of adjusted R sqaured score
</p>
<p style="text-indent: 20px;">
♦ Random Forest performed the best. Implemented Hyperparameter Tuning using RandomisedSearchCV
</p>
<p style="text-indent: 20px;">
♦ Finally pickled the optimized Random Forest model and built a WebApp using HTML, CSS and Flask which was deployed on Railway.app Cloud using Docker Image
</p>

Docker Container Registry on DockerHub: lukechugh/flight_fare_prediction

# Below is the screenshot of my WebApp

![Capture](https://github.com/luke-chugh/flight-fare-prediction-webapp/blob/main/screenshots/1.png)

# Installation:
To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```
To use this app run the following command in a command prompt/ terminal inside the directory of this cloned repository:
```
python app.py
```
# Author:
[Luke Chugh](https://www.linkedin.com/in/luke-chugh-2b2043181/)
