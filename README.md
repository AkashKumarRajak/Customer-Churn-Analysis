#📊 Telco Churn Analysis<br>

#📌 Overview<br>
This project aims to analyze customer churn in a telecom company using Python. By performing data preprocessing, exploratory data analysis (EDA), and visualizations, we aim to identify key factors influencing customer churn and derive business insights.<br>

#📂 Dataset<br>
The dataset used in this analysis is Customer Churn.csv, which contains customer details such as:<br>

Demographic Information (gender, senior citizen status, etc.)<br>
Account Information (tenure, payment method, contract type, etc.)<br>
Service Usage (monthly charges, total charges, internet service type, etc.)<br>
Churn Label (indicating whether the customer has left the service)<br>

#🛠 Technologies Used<br>
Python 🐍<br>
Pandas 📊<br>
NumPy 🔢<br>
Matplotlib & Seaborn 📈<br>

#📌 Key Steps in the Project<br>

1.Data Preprocessing<br>

Handling missing values (e.g., replacing blanks with 0 for tenure)<br>
Encoding categorical variables (e.g., converting SeniorCitizen from 0/1 to Yes/No)<br>

2.Exploratory Data Analysis (EDA)<br>

Understanding churn distribution (e.g., ~26.54% churn rate)<br>
Visualizing churn patterns across different customer segments<br>
Identifying factors correlated with churn<br>

3.Insights & Business Recommendations<br>

Which customer groups are more likely to churn?<br>
How do pricing, contract types, and services affect retention?<br>
What actions can be taken to reduce churn?<br>

#📌 How to Run the Notebook<br>

1.Install dependencies:<br>
pip install pandas numpy matplotlib seaborn<br>

2.Run the Jupyter Notebook:<br>
jupyter notebook "Telco Churn Analysis.ipynb"<br>

3.Ensure Customer Churn.csv is available in the working directory.
