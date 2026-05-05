# Bank Marketing Data Analysis & Subscription Prediction
## Project Overview
This project analyzes a bank marketing dataset to understand customer behavior and build a predictive model to determine whether a client will subscribe to a term deposit. By identifying the key drivers of success, this framework helps improve the effectiveness of future telemarketing campaigns.
## Key Features
## Exploratory Data Analysis (EDA): 
Performed data inspection and visualized subscription distributions, uncovering that only ~11.3% of contacts resulted in a subscription.
## Data Preprocessing: 
Cleaned the dataset by removing zero-duration call anomalies and utilized One-Hot Encoding to handle categorical variables and interval-based economic indicators.
## Predictive Modeling: 
Developed a Logistic Regression classifier to predict customer outcomes.  Business Insights: Generated feature importance rankings, identifying call duration and Consumer Price Index as the most significant predictors of subscription.
## Technical Results
Accuracy: 91%  
Precision (for 'yes'): 0.70  
Recall (for 'yes'): 0.45
## Primary Predictor: 
Call Duration (longer engagement strongly correlates with "yes" responses).
## Tech Stack 
## Language: 
PythonLibraries: Pandas, Seaborn, Matplotlib, Scikit-Learn  
## How to Use
Clone the repository.Install dependencies: pip install -r requirements.txt.Run the Jupyter Notebook: Bank_Marketing_Inspection.ipynb.
