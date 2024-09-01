# SpaceX
SpaceX Falcon 9 first stage LandingPrediction
In this capstone, we will predict if the Falcon 9 first stage will land successfully. SpaceXadvertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; otherproviders cost upward of 165 million dollars each, much of the savings is because SpaceXcan reuse the first stage. Therefore if we can determine if the first stage will land, we candetermine the cost of a launch. This information can be used if an alternate company wantsto bid against SpaceX for a rocket launch. 

Collecting the data
Request to the SpaceX API 
Clean the requested data and formatting

Web scraping Falcon 9 and Falcon Heavy Launches Records from Wikipedia
Web scrap Falcon 9 launch records with BeautifulSoup : 
Extract a Falcon 9 launch records HTML table from Wikipedia 
Parse the table and convert it into a Pandas data frame 

Data wrangling
Exploratory Data Analysis 
Determine Training Labels 

Using SQL
Understand the Spacex DataSet 
Load the dataset into the corresponding table in a Db2 database 
Execute SQL queries to answer assignment questions

Exploring and Preparing Data
Perform exploratory Data Analysis and Feature Engineering using Pandas and Matplotlib:
Exploratory Data Analysis
Preparing Data Feature Engineering

Launch Sites Locations Analysis with Folium
Mark all launch sites on a map
Mark the success/failed launches for each site on the map
Calculate the distances between a launch site to its proximities
Find some geographical patterns about launch sites.

Build a Dashboard Application with Plotly Dash
Add a Launch Site Drop-down Input Component
Add a callback function to render success-pie-chart based on selected site dropdown
Add a Range Slider to Select Payload
Add a callback function to render the success-payload-scatter-chart scatter plot

Machine Learning Prediction
Perform exploratory Data Analysis and determine Training Labels
create a column for the class
Standardize the data
Split into training data and test data
Find best Hyperparameter for SVM, Classification Trees and Logistic Regression
Find the method performs best using test data
