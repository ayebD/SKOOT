# SKOOT 
Skoot application: recruit football player with the help of machine learning 

Modules
The Skoot application consists of three main modules:

Datasets
The Datasets module handles data loading, processing, and management. It enables users to import data from multiple sources, such as CSV, Excel, or SQL databases. The module also includes functions for data exploration and visualization, allowing users to gain insights into their data.

Predictions
The Predictions module contains various machine learning models and algorithms for making predictions on the processed data. This includes supervised learning methods, such as regression and classification, as well as unsupervised techniques like clustering and dimensionality reduction. Users can train models, make predictions, and evaluate their performance using a variety of metrics.

Preprocessing
The Preprocessing module is responsible for preparing the data for machine learning tasks. This includes cleaning, normalizing, and encoding the data, as well as handling missing values and outliers. The module offers a range of preprocessing techniques, allowing users to select the most suitable methods for their specific dataset and problem.

API
The API module is built using Flask, a popular Python web framework. The API exposes a set of endpoints that can be used to interact with the Skoot application. The endpoints include:

/data - give the stats of all the player we have

/data/<player name> - give the data of a single player




