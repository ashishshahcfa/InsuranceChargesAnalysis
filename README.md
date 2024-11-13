# Insurance Claims Data Analysis Using Python
**Project Overview**

This project involves analyzing an insurance dataset to identify trends in insurance claims, risk factors, and customer demographics. The analysis includes exploring the relationship between various customer characteristics (such as age, smoker status, and region) and the insurance charges they incur. We also build a predictive model using linear regression to estimate insurance charges based on customer demographics.

**Key Tools & Libraries**

**Pandas:** Data manipulation and cleaning.

**NumPy:** Numerical computations.

**Matplotlib & Seaborn:** Data visualization.

**Scikit-learn:** Machine learning for building the predictive model (Linear Regression).

**Objective**
Analyze trends and relationships in the dataset.
Understand how variables like age, smoker status, region, etc., impact insurance charges.
Build a linear regression model to predict insurance charges based on customer demographics.

**Steps & Methodology**

**1. Data Loading and Preprocessing**
The dataset is loaded into a Pandas DataFrame.
Data cleaning is performed to ensure there are no missing or incorrect values.
Categorical features are encoded into numerical representations where necessary.

**2. Exploratory Data Analysis (EDA)**
Visualize Distributions: Plot the distribution of key variables like age, charges, and smoker status.
Correlation Analysis: Identify relationships between numeric variables (e.g., charges, age).
Boxplot Analysis: Understand how charges vary based on categorical variables like smoker status and region.

**3. Predictive Modeling**
Linear Regression: Using scikit-learn, the model is trained to predict insurance charges.
The data is split into training and test sets.
A linear regression model is trained on the data, and its performance is evaluated using metrics such as Root Mean Squared Error (RMSE).

**4. Data Visualization**
Visualizations are created using matplotlib and seaborn to gain insights into the data and model predictions.
Heatmaps of correlations between numerical features.
Regression plots to visualize the relationship between variables (e.g., age vs. charges).
Boxplots to compare charges between smokers and non-smokers.

**Dataset:**

The dataset used in this project is sourced from Kaggle: Insurance Dataset. 
The dataset contains the following columns:

age: Age of the primary beneficiary.

sex: Gender of the primary beneficiary.

bmi: Body mass index.

children: Number of children/dependents covered by health insurance.

smoker: Whether the beneficiary is a smoker (yes/no).

region: Geographical region of the beneficiary.

charges: Medical charges billed to the beneficiary.

Setup and Installation:

Prerequisites:

To run this project, ensure you have the following Python libraries installed:

**pandas,
numpy,
matplotlib,
seaborn,
scikit-learn**

**License:**
This project is open-source and available under the MIT License.

Author
Ashish Shah
GitHub Profile: @ashishshahcfa
