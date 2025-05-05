# Duong-Tran-IBM-Applied-Data-Science-Capstone
Hi all, 
This is my project for IBM Applied Data Science Capstone course. Please contact me if you have any question. 
Thank you for reading.


Objectives
The project is structured into several comprehensive modules, each designed to build on the previous one, culminating in a robust predictive model. Below is a detailed description of the tasks and goals achieved in each module:

1. Request to the SpaceX API and Data Wrangling
Data Collection: We initiated our project by making a GET request to the SpaceX API to gather historical launch data. This data included various parameters essential for our analysis.
Data Cleaning: After obtaining the data, we performed cleaning and formatting to ensure consistency, removing any anomalies or missing values, and preparing it for analysis.
2. Web Scraping Falcon 9 Launch Records
Web Scraping with BeautifulSoup: We extracted Falcon 9 launch records from Wikipedia using BeautifulSoup, a powerful Python library for web scraping.
Data Parsing: The extracted HTML table was parsed and converted into a Pandas DataFrame, facilitating easy manipulation and analysis of the data.
3. Exploratory Data Analysis (EDA) and Training Labels
Exploratory Data Analysis: We conducted extensive EDA using visualization tools like Matplotlib and Seaborn to uncover patterns and correlations in the data.
Training Labels: Identified and labeled the training data, crucial for the subsequent machine learning models.
4. Database Integration
Loading Data into Db2: We loaded the dataset into a Db2 database to leverage SQL for structured querying and analysis.
Executing SQL Queries: Executed various SQL queries to derive insights and answer specific questions related to the launch data.
5. Feature Engineering and Visualization
Feature Engineering: Created new features from the existing data to enhance the predictive power of our models.
Visualization with Folium: Used Folium to create interactive maps, marking launch sites and visualizing success and failure rates, helping to identify geographical patterns.
6. Interactive Visual Analytics with Plotly Dash
Building the Dash Application: Developed an interactive Plotly Dash application, allowing users to perform real-time visual analytics on the SpaceX launch data.
User Interaction Components: Incorporated dropdown lists and range sliders to enable dynamic interaction with pie charts and scatter plots, making the analysis more intuitive and engaging.
7. Machine Learning Models and Hyperparameter Tuning
Data Standardization and Splitting: Standardized the dataset and split it into training and test sets to ensure robust model evaluation.
Hyperparameter Tuning: Performed hyperparameter tuning using GridSearchCV for various models, including SVM, Classification Trees, and Logistic Regression.
Model Evaluation: Evaluated each model's performance on the test data to identify the best-performing model.
Results
Decision Tree Classifier: Achieved the highest accuracy of 0.9444 on the test set, making it the best-performing model.
SVM and K-Nearest Neighbors: Both models attained an accuracy of 0.8333 on the test set.


Conclusion
Through meticulous data analysis, feature engineering, and model tuning, this project successfully predicted the landing success of the Falcon 9 first stage. The insights gained are invaluable for estimating launch costs and aiding companies in their competitive bids against SpaceX.

