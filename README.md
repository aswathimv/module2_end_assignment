# module2_end_assignment

# Employee Data Analysis
# Overview
  
      This project it analyzes the emplopyee dataset of ABC Company,with 458 employee records and 9 categories.THe main objective of this project is to preprocess      the given data according to our needs,explore the given dataset,conclude meaningfull insights regarding employee distribution,position distribution,salary          expenditure,and finding the relationship between age and salary,and finally plotting them for better understandability
    The project was implemented using Python with the Pandas, NumPy, Matplotlib, and Seaborn libraries.

# Dataset Information
  
  The dataset contains information about employees such as,
  
  1)Name	
  
  2)Team	
  
  3)Number	
  
  4)Position	
  
  5)Age	
  
  6)Height	
  
  8)Weight
  
  9)College	
  
  10)Salary
  
# Data Preprocessing
  
    The dataset was preprocessed before analyzing for easy and accurate results.
  
# Preprocessing steps

  **->** Importing the dataset to PANDAS DATAFRAME
  
  **->** Values in the **"Height"** column was replaced with randomly generated integers between 150 cm and 180 cm using NumPy (randomint function)to satisfy the project requirements and random.seed() function was used so that the random numbers generated for height remains the same each time the code runs.

# Data Analysis

The following analysis were carried out:

# 1.Distribution of employees across each team

  **->** Calculated the number of employees in eachteam.
  
  **->** Computed the percentage of contribution of each team relative to the total manpower.
  
# 2. Employee Distribution by Position

**->** Segregated employees based on their job positions.

**->** Determined the number of employees occupying each position.

# 3. Predominant Age Group
**->** Grouped employees into age intervals.

**->** Identified the age group containing the highest number of employees.

# 4. Salary Expenditure Analysis

**->** Calculated the total salary expenditure for each team.

**->** Calculated the total salary expenditure for each employee position.

**->** Identified the teams and positions with the highest salary expenditure.

# 5. Correlation Between Age and Salary
**->** Measured the relationship between employee age and salary.

**->** Computed the correlation between age and salary to determine whether the two variables are related.

**->** Analyzed the strength of the relationship between age and salary using correlation analysis and visualized the relationship using a heatmap.

# Data Visualizations

The following visualizations were created to effectively present the analysis:

**Bar Chart** – Employee distribution across teams.

**Pie Chart** – Employee distribution by position.

**Count Plot** – Predominant age group distribution.

**Horizontal and Vertical Bar Charts** – Team-wise and position-wise salary expenditure.

**Scatter Plot with Regression Line** – Correlation between age and salary.

# Key Insights

Based on the analysis and visualizations, the following conclusions were drawn:

Employee distribution is uneven across different teams, with some teams having a more strength than others.
Some job positions employ more individuals, indicating that these roles are central to the organization's operations.
The majority of employees belong to a younger age group, indicating a relatively young workforce.
Salary expenditure differs significantly among teams and positions, with a few teams contributing the highest share of total salary expenses.
The correlation coefficient between Age and Salary is approximately 0.214, indicating a weak positive correlation. This suggests that salary tends to increase 
slightly with age; however, age alone is not a strong predictor of salary, and other factors such as experience, position, and performance likely influence 
the salary increment.

# Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

# Conclusion

     This project demonstrates the effective use of data preprocessing, exploratory data analysis (EDA), and data visualization to gain meaningful insights from the ABC Company employee dataset. The analysis highlights employee distribution across teams and positions, identifies the predominant age group, examines salary expenditure, and explores the relationship between age and salary. Overall, the findings provide a better understanding of the organization's workforce and can support informed decisions related to workforce management, salary planning, and resource allocation.



