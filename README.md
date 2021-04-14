# Machine Learning in Spark 

<h2>Objective</h2>
<p>Predicting the year in million song dataset with machine learning (mllib package) using pyspark</p>

<h2>Data</h2>
"Year Prediction MSD Dataset" from UCI Machine Learning Repository is used for this project
https://archive.ics.uci.edu/ml/datasets/yearpredictionmsd

<h2>Data preprocessing</h2>
<ul>
  <li>Load the dataset and use min max scaling to scale features between 0 and 1</li>
    <li>Normalize the labels by subtracting min year</li>
    <li>Split the dataset into train (70%), test (20%), and validation (10%) set</li>
  </ul>

<h2>Model</h2>
Using Linear Regression 
