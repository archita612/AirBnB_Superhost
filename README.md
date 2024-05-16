<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>

<h1>Airbnb Superhost Status Prediction</h1>

<p>This project aims to predict the Superhost status of Airbnb properties by determining their earning potential and success as a host, focusing on two main factors: occupancy rate and overall property ratings.</p>

<h2>Project Overview</h2>
<p>We utilized various modeling techniques to identify the pivotal factors influencing the success of Airbnb properties in Houston. The key factors impacting earning potential were categorized into two types:</p>
<ul>
    <li><strong>Controllable Factor</strong> - Overall Guest Ratings</li>
    <li><strong>Uncontrollable Factor</strong> - Occupancy Rates</li>
</ul>

<p>We conducted data cleaning on the real dataset, replacing missing values using clustering techniques. Our exploration of model selection included Linear Regression, Polynomial Regression, Random Forest, Gradient Boosting, Lasso, and Ensemble models, based on R-squared and RMSE scores. Through the best model, we identified influential factors and provided actionable insights for property owners to positively impact their revenue.</p>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#dataset">Dataset</a></li>
    <li><a href="#data-cleaning">Data Cleaning</a></li>
    <li><a href="#modeling-techniques">Modeling Techniques</a></li>
    <li><a href="#results">Results</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
</ul>

<h2 id="dataset">Dataset</h2>
<p>The dataset used in this project was sourced from Airbnb listings in Houston. It includes various attributes such as property details, host information, ratings, and occupancy rates.</p>

<h2 id="data-cleaning">Data Cleaning</h2>
<p>Data cleaning involved handling missing values using clustering techniques to ensure the dataset was ready for analysis. This step was crucial to maintain data integrity and improve the accuracy of our models.</p>

<h2 id="modeling-techniques">Modeling Techniques</h2>
<p>We explored several modeling techniques to determine the best fit for our data:</p>
<ul>
    <li>Linear Regression</li>
    <li>Polynomial Regression</li>
    <li>Random Forest</li>
    <li>Gradient Boosting</li>
    <li>Lasso Regression</li>
    <li>Ensemble Models</li>
</ul>
<p>The models were evaluated based on their R-squared and RMSE scores to identify the most effective model in predicting earning potential and Superhost status.</p>

<h2 id="results">Results</h2>
<p>The best performing model highlighted that both overall guest ratings and occupancy rates are significant factors influencing the earning potential of Airbnb properties. These findings provide actionable insights for property owners to enhance their listings and potentially achieve Superhost status.</p>

<h2 id="license">License</h2>
<p>This project is licensed under the MIT License - see the <a href="LICENSE">LICENSE</a> file for details.</p>

</body>
</html>
