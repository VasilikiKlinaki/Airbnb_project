# Airbnb Data Analytics
### **Description:**

This project performs exploratory data analysis on Airbnb listings in Athens using data from Inside Airbnb. The goal is to uncover patterns in pricing, availability, and host characteristics by examining the structure and quality of the dataset.

You can find the dataset on https://insideairbnb.com/get-the-data/ with a detailed description.

### **Python libraries used:** 

- pandas: data cleaning and transformation
- matplotlib: visualizing data, creating various charts
- scikit-learn: ML models and evaluation metrics


## **Project overview**

**1. Data cleaning and transformation**

Checking the dataset for missing values and duplicates, shortening column names and adding new derived columns.

**2. Exploratory Data Analysis**

Answering questions regaring the dataset by using data transformation and filtering, and creating various types of charts: 








**3. Machine Learning - Predicting** 

- **Pre-processing data**: dropping irrelevant columns, removing rows with missing values and duplicates, encoding categorical data into numeric.
- **Feature Engineering**: calculating features' correlations with the target variable and removing irrelevant ones, dropping some features that highly correlate with each other to avoid multicollinearity.
- **Modeling**: splitting the data into training and testing sets, scaling the features, creating and evaluating machine learning models.


## **Notes**

How to run the code:

- Download the dataset `detailed_listings.csv` from https://insideairbnb.com/get-the-data/
- In case you change the file name, also change the data path in the code `pd.read_csv('<YOUR DATA PATH>')`
- Download the processed dataset for the dashboard
