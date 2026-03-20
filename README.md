# Employee Data Analysis Project
# **Project Overview**

This project involves analyzing an employee dataset containing 458 records and 9 attributes. The objective is to perform systematic data preprocessing, exploratory data analysis (EDA), and visualization to extract meaningful insights about employee distribution, roles, age patterns, salary expenditure, and relationships between variables.

The project emphasizes not only performing analysis but also explaining the reasoning behind each step to ensure clarity and correctness.

dataset: https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2FSruthiTS24%2FModule-End-Assignmnet_2_Python_ABC_Company%2Frefs%2Fheads%2Fmain%2FABC%2520Company.xlsx&wdOrigin=BROWSELINK
# Tools and Technologies used
* Python – Core programming language
* Pandas – Data manipulation
* NumPy – Numerical operations
* Matplotlib & Seaborn – Data visualization
* Jupyter Notebook – Interactive development environment
# Dataset Description
*The dataset consists of the following columns:
* Name – Employee name
* Team – Team to which the employee belongs
* Number – employee number
* Position – Role of the employee
* Age – Age of the employee
* Height – Height of the employee
* Weight – Weight of the employee
* College – Educational background
* Salary – Salary of the employee
# Data Preprocessing
The following steps were performed to clean and prepare the dataset:
* Missing values in the Salary column were replaced with the mean value
  
  Reason : Using the mean preserves the overall distribution and avoids loss of data that would occur if rows were removed
* Missing values in the College column were filled with "Unknown"
  
  Reason : Since College is a categorical variable and not central to the analysis, replacing missing values with a placeholder avoids unnecessary data loss
* The Height column was corrected using random values between 150 and 180
* Checked for duplicate records (none found)
# Analysis & Visualizations
**1. Distribution of Employees Across Teams**
* A countplot was used to visualize the number of employees in each team
* The percentage distribution was also calculated
* Reason for using countplot:
Countplot is ideal for categorical data and helps in understanding how employees are distributed across different teams
* Insight:
Employees are fairly evenly distributed across teams, with minor variations in counts
**2. Segregation of Employees by Position**
* A countplot was used to show the number of employees in each position
* Reason for using countplot:Position is a categorical variable, and countplot clearly shows the frequency of each role
* Insight: Certain positions such as 'SG' and 'PF' have higher representation compared to others
**3. Predominant Age Group**
* Used histogram with defined bins to analyze age distribution
* Reason for using histogram: Age is a numerical variable, and histogram is the most suitable method to observe its distribution and identify concentration (peaks)
* Insight: The peak occurs in the 25–30 age range, and most employees fall between 20–30 years, indicating a predominantly young workforce
**4. Salary Expenditure Analysis**
* Total salary expenditure was calculated for both teams and positions.
* Bar charts were used for visualization
* Reason for using bar charts: Bar charts are effective for comparing aggregated numerical values across categories.
* Insights: The Cleveland Cavaliers have the highest salary expenditure among teams. Positions such as 'C' and 'PG' contribute the most to salary expenditure.
**5. Correlation Between Age and Salary**
* A scatter plot was used to visualize the relationship between Age and Salary.
* Correlation value was calculated as 0.21.
* Reason for using scatter plot: Scatter plots are ideal for identifying relationships between two numerical variables.
*Insight: There is a weak positive correlation, meaning salary tends to increase slightly with age, but the relationship is not strong.
# Conclusion
This project highlights the importance of:
* Proper data cleaning for accurate analysis
* Choosing appropriate visualization techniques
* Interpreting results to derive meaningful insights
The analysis provides a clear understanding of workforce structure, salary distribution, and employee demographics.
# How to Run the Project
* Download the dataset
* Open the Jupyter Notebook
* Run all cells sequentially to reproduce the analysis
