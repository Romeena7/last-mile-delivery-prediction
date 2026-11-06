# Last-Mile Delivery Time Prediction and Route Optimization for an E-Commerce Logistics Company #

## _PROJECT OVERVIEW_

This project focuses on predicting delivery times and identifying route optimization opportunities in an e-commerce logistics environment. Using data science and machine learning techniques, the project analyzes delivery performance, preprocesses logistics data, explores operational patterns, and develops predictive models to support more efficient logistics operations.

The project was completed through four phases:

- Week 1: Project Planning and Dataset Exploration
- Week 2: Data Cleaning and Preprocessing
- Week 3: Exploratory Data Analysis and Visualization
- Week 4: Predictive Modeling and Route Optimization

## _Objectives_ 
- Analyze factors influencing delivery time.
- Improve data quality through preprocessing techniques.
- Explore delivery patterns using statistical analysis and visualization.
- Build machine learning models for delivery time prediction.
- Identify key variables affecting logistics performance.
- Propose route optimization recommendations based on predictive insights.

> __Dataset Information__
  
 _Dataset: Olist Delivery Time Dataset_ 

|Records: 96,478 |
|----------------|
|Features: 24    |

_Target Variable: delivery_time_days_

> Key Features: 

- distance_km
- estimated_delivery_days
- total_freight
- payment_value
- product_weight_g


 ## _Dataset Statistics_
 
|       Metric	          |      Value       |
|-------------------------|------------------|
|Original Records	        |   96,478         |
|Features	                |    24            |
|Missing Values Identified|    1,917         |
|Outliers Detected	      |     4,896        |
|Cleaned Records	        |     91,582       |
|Target Variable	        |delivery_time_days|


## Machine Learning Results 
- Model Comparison
 
|     Model	         |MAE | RMSE |R² Score|
|--------------------|----|------|--------|
|Linear Regression   |3.81|4.95	 |0.337   |
|Decision Tree	     |4.88|	6.55 |-0.159  |
|Random Forest       |3.60|	4.72 |0.397   |
|Tuned Random Forest |3.54|	4.63 |0.421   |

### Best Performing Model

Tuned Random Forest Regressor

Key outcomes:

+ Reduced prediction error.

+ Improved generalization performance.

+ Explained approximately 42.1% of delivery time variability.

+ Identified the most influential logistics factors affecting delivery duration.

### Key Findings

- Same-state deliveries have the strongest influence on delivery performance.
- Delivery distance significantly affects delivery duration.
- Estimated delivery days provide valuable predictive information.
- Seasonal demand patterns impact logistics operations.
- Route optimization and regional fulfillment centers can improve delivery efficiency.


## _Project Workflow_

Week 1: Project Planning and Dataset Exploration
Defined project objectives and logistics problem statement.
Identified key performance indicators (KPIs).
Explored dataset structure and business context.
Prepared project roadmap.

Week 2: Data Cleaning and Preprocessing
Missing value analysis and treatment.
Duplicate record assessment.
Outlier detection using IQR.
Data normalization using Min-Max Scaling.
Prepared cleaned dataset for analysis.

Week 3: Exploratory Data Analysis
Descriptive statistics.
Delivery time distribution analysis.
Correlation heatmap analysis.
Distance vs delivery time analysis.
Monthly order trend analysis.
Business insight generation.

Week 4: Predictive Modeling and Optimization
Built Linear Regression model.
Built Decision Tree Regressor model.
Built Random Forest Regressor model.
Performed hyperparameter tuning.
Conducted feature importance analysis.
Developed route optimization recommendations.

### Technologies Used
- Programming Languages
Python
SQL
- Data Analysis
Pandas
NumPy
- Visualization
Matplotlib
Seaborn
- Machine Learning
Scikit-learn
- Tools
Jupyter Notebook
GitHub


> Author
Romeena Shaikh

B.Tech Computer Science Engineering (Artificial Intelligence & Data Science)

Data Science Intern | Aspiring Machine Learning Engineer

[GitHub]( https://github.com/Romeena7)
