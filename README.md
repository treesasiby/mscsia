# Student Lifestyle and Academic Performance Analysis

## Overview
This project investigates how lifestyle factors influence students' academic performance (CGPA). The analysis examines the relationships between study hours, sleep duration, social media usage, physical activity, and stress level using exploratory data analysis, visualization, correlation analysis, and multiple linear regression.

## Dataset
The dataset contains 20,538 student records with the following variables:
- Student_ID
- Age
- Gender
- Department
- CGPA
- Sleep_Duration
- Study_Hours
- Social_Media_Hours
- Physical_Activity
- Stress_Level
- Depression

## Methods
The following analyses were performed:
- Data cleaning and exploration using Pandas
- Descriptive statistics
- Data visualization using Matplotlib and Seaborn
- Correlation analysis using a heatmap
- Multiple linear regression using Statsmodels

## Key Findings
- Study hours have a positive and statistically significant relationship with CGPA.
- Social media usage has a negative and statistically significant relationship with CGPA.
- Stress level has a slight negative effect on CGPA.
- Sleep duration and physical activity were not statistically significant predictors of CGPA.
- The regression model explains approximately 2% of the variation in CGPA (R² = 0.020), suggesting that other factors also influence academic performance.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Jupyter Notebook

## Author
Treesa Siby

Paris School of Economics   









       ## Installation

1. Clone the repository:

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/mscsia.git
```

2. Create the environment:

```bash
conda env create -f environment.yml
```

3. Activate the environment:

```bash
conda activate mscsia
```

## Running the Project

1. Open the project folder.

2. Start Jupyter Notebook:

```bash
jupyter notebook
```

3. Open `treesa_sibby_assignment.ipynb`.

4. Click **Run All** to execute the notebook and reproduce all analyses, visualizations, and the regression model.