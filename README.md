Dash App for Iris Dataset Visualization
Description
This project demonstrates a Dash-based web application to visualize the famous Iris dataset. The app allows users to interactively explore relationships between features in the dataset, such as sepal length, sepal width, petal length, and petal width, through scatter plots and other visualizations.

Dataset
The Iris dataset used in this project is a public dataset originally published by Ronald A. Fisher in 1936. It is widely used for machine learning and statistical analysis tasks.

Source: Fisher, R.A. (1936). The Use of Multiple Measurements in Taxonomic Problems.
The dataset is loaded from scikit-learn.

Features: Sepal length, sepal width, petal length, and petal width.
Target Classes: Iris-setosa, Iris-versicolor, and Iris-virginica.
Steps in the Project
Data Preparation:

Loaded the Iris dataset using scikit-learn.
Created a DataFrame with feature names and target values.
Performed basic data exploration to ensure no missing values.
Dash Application:

Initialized a Dash app using the dash library.
Defined the app layout with dropdowns for selecting features and visualizations.
Implemented interactive scatter plots using Plotly.
Added hover functionality to display data points dynamically.
Set up callbacks for interactivity, linking dropdown selections to plot updates.
Visualization:

Dynamic scatter plot showing feature relationships.
Dropdown for selecting X and Y axes for the scatter plot.
Visual cues (e.g., colors) to distinguish between the target classes.
Libraries Used
The following Python libraries were used:

Data Manipulation: pandas
Machine Learning Dataset: scikit-learn
Web Framework: dash
Visualization: plotly
How to Run
Clone this repository:
bash
Copy code
git clone https://github.com/Sid-Ghafoorzai/Dash-Iris-App.git
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Dash app:
bash
Copy code
Dash_APP_IRIS.py
Open your browser and navigate to http://127.0.0.1:8050/ to view the application.
Results
The Dash app provides an intuitive way to visualize the Iris dataset, offering insights into the relationships between features and the separability of the target classes.

Future Work
Add more visualization options, such as histograms or pair plots.
Incorporate machine learning predictions directly into the app.
Improve the user interface for better accessibility.


Author
Sadaqat Ghafoorzai
For questions or suggestions, feel free to reach out!