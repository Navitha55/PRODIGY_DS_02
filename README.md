# PRODIGY_DS_02
Perform data Cleaning and (EDA) on a dataset, Titanic_Dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.
# Titanic Dataset Analysis
This project involves exploring the Titanic dataset using Python and various data analysis libraries, such as pandas, numpy, matplotlib, and seaborn. The Titanic dataset contains information about passengers on board the Titanic and whether they survived or not.

# Starting with...
To get started, make sure you have the necessary Python libraries installed. You can install them using pip:
pip install pandas numpy matplotlib seaborn

# Data Cleaning
In the data cleaning phase, we performed the following operations:

- Handling missing values:
- Age: Missing values were replaced with the median age.
- Embarked: Missing values were replaced with the mode (most common value).
  
# Exploratory Data Analysis (EDA)
## Data Visualization
We used data visualization techniques to explore relationships and patterns in the dataset:

## Survival by Sex: I created a count plot to visualize survival by gender.
- ![image](https://github.com/Navitha55/PRODIGY_DS_02/assets/167078330/61d66b94-365e-483e-be8c-54de20eb35d1)

## Survival by Passenger Class: I created a count plot to visualize survival by passenger class.
- ![image](https://github.com/Navitha55/PRODIGY_DS_02/assets/167078330/b7bc6b81-d291-43fa-9c3f-5d7d84bda2b1)

## Survival by Age: I used a histogram to visualize the age distribution of survivors and non-survivors.
- ![image](https://github.com/Navitha55/PRODIGY_DS_02/assets/167078330/b3126101-2ade-484a-af5d-b7e27fa1863d)

## Survival by Fare: I used a histogram to visualize the fare distribution of survivors and non-survivors.
- ![image](https://github.com/Navitha55/PRODIGY_DS_02/assets/167078330/6a4a1220-d25f-4317-82ec-9c568c772b98)

## Correlation Heatmap: I generated a heatmap to visualize the correlation between various numerical features and survival.
- ![image](https://github.com/Navitha55/PRODIGY_DS_02/assets/167078330/1de5e2e7-5350-4ac3-8e09-e2c6a3f1a8af)


## Age and Fare Distribution
We explored the distribution of passengers' ages and fares using histograms.

# Data Preprocessing
One-hot Encoding: We performed one-hot encoding on the 'Embarked' column to convert categorical data into numerical format.

# Finally...
This analysis provides valuable insights into the Titanic dataset, including the distribution of passengers, relationships between variables, and patterns related to survival. Notable findings include the higher survival rate among females, first-class passengers, children, and passengers who paid higher fares.

