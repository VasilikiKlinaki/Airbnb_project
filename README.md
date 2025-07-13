# Airbnb Data Analytics
### **Description:**



### **Python libraries used:** 

- pandas: data cleaning and transformation
- matplotlib: visualizing data, creating various charts
- scikit-learn: ML models and evaluation metrics
- streamlit: creating an online dashboard


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

- Ensure to download the necessary packages as in `requirements.txt`
- Download the dataset `` from Kaggle
- In case you change the file name, also change the data path in the code `pd.read_csv('<YOUR DATA PATH>')`
- Download the processed dataset for the dashboard
- Run the Streamlit dashboard by typing `streamlit run energy_dashboard.py` on the terminal
