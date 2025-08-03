# Carolina-Cupboard-Data-Analysis
Analysis of on-campus food pantry demand from the UNC-Chapel Hill Carolina Cupboard. 

# Overview
This project analyzes four semesters of student pantry usage data at UNC-Chapel Hill. It explores demand trends, patron behavior, and predictive insights to help Carolina Cupboard optimize operations and better serve the student community.

# Key Features
- Total food weight distribution by semester
- Repeat vs. new patron analysis
- Predictive modeling of future food demand using Linear Regression

# Data 
- Cleaned and merged data from four semesters (Fall 2023 to Spring 2025)
- Includes anonymized student IDs, visit dates, and number of bags distributed per visit
- Assumes 1 bag ≈ 6.11 lbs for total weight calculations

# Tools Used
- Python (Pandas, NumPy)
- Matplotlib & Seaborn (for visualizations)
- scikit-learn (for regression modeling)
- Jupyter / Kaggle Notebook

# Insights
Overall, demand for the Carolina Cupboard has increased year over year, and we can observe a general trend where there were few patrons in Fall 2023 (261 entries), followed by a rise in Spring 2024 (462 entries). Then, the following year, there is more demand in Fall 2024 (362 entries) than in the previous fall (Fall 2023). Finally, there is an increase in Spring 2025 (597 entries). The trend is cyclical, following the cycle of new students coming onto campus and slowly learning about the Carolina Cupboard. This is also further supported by my analysis of new patrons and the total weight of items by semester. 
Despite the cyclical demand trends, the overall rising demand year over year shows positive signs for the Carolina Cupboard. Hopefully, this trend continues for many years to come. 
To increase demand, the Carolina Cupboard may want to consider implementing feedback forms to better retain recurring customers, as there are just as many one-time patrons as repeat patrons. 
It is important to note that my findings suffer from imperfect data. I made assumptions for missing bag weight by finding the average bag weight and applying it to other semesters. Additionally, the data set is relatively small, only spanning 4 semesters, or 2 years. To better analyze the trends, I would need at least 8 semesters, or 4 years of data. This lack of data also contributes to the prediction model having such a high MSE.  
