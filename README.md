# Predictive-Modeling-of-Homestay-Prices

## Objective
This project aims to predict homestay prices for Airbnb properties using a regression model. The goal is to uncover key factors influencing price fluctuations and provide actionable business insights for better pricing strategies. The analysis helps to inform decisions regarding the Airbnb marketplace by leveraging data analytics and machine learning techniques.

## Tools & Technologies
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib
- **Tools**: Jupyter Notebook
- **Techniques**: Data Cleaning, KNN Imputation, Outlier Detection (IQR), Regression Analysis, Data Visualization

## Project Description

This project explores the use of machine learning techniques to predict the prices of Airbnb homestays. We utilized a combination of statistical analysis, feature engineering, and machine learning algorithms to identify key drivers of pricing decisions and optimize our model to provide actionable business insights.

We focused on the following aspects:

1. **Exploratory Data Analysis (EDA)**:
   - A thorough EDA process was conducted using Python libraries such as Pandas and Matplotlib to understand data distribution, relationships between variables, and outliers.
   - Visualized relationships using heatmaps, boxplots, and correlation matrices to identify trends and potential anomalies in the data.
   - ![image](https://github.com/user-attachments/assets/91109e65-b143-4708-b71e-ebc4cce9a8ec)


2. **Data Preprocessing**:
   - **Missing Values Treatment**: Missing data was handled using advanced imputation methods. We experimented with mean, median, and K-Nearest Neighbors (KNN) imputation to predict missing values and improve data completeness.
   - **Outlier Detection and Treatment**: Outliers were detected using Interquartile Range (IQR) and boxplot visualizations. This step was critical to ensure the robustness of the model.
![image](https://github.com/user-attachments/assets/be62dae2-2318-40ff-b4b5-e8eb4aed9e25)
![image](https://github.com/user-attachments/assets/23cdfe7c-f916-49d0-b175-b075a3ae60c2)

3. **Feature Engineering**:
   - Created new features by analyzing correlations between existing variables and the target variable (log_price).
   - This included transforming categorical variables, scaling continuous variables, and selecting important features for model training.

4. **Modeling and Evaluation**:
   - **Train-Test Split**: We created six datasets, including three with outlier treatment and three without, to assess model performance under different conditions.
   - **Regression Modeling**: A regression model was built using Python, focusing on predicting homestay prices. We evaluated the model’s performance using various metrics such as RMSE and accuracy scores.
   - Achieved a **50.3% accuracy** on the KNN-imputed dataset without outlier treatment, outperforming other models across all datasets.

## Methodology

### 1. Data Understanding & Cleaning:
- Loaded Airbnb data into Pandas DataFrame for initial inspection and data quality assessment.
- Handled missing values through a multi-step process:
   - Created three datasets using mean, median, and KNN imputation for a comparative analysis.
   - Analyzed imputation results to select the best-performing dataset based on predictive accuracy.

### 2. Outlier Detection & Treatment:
- Outliers were detected using the Interquartile Range (IQR) method and visualized through boxplots.
- Developed three datasets with outlier treatment (collapsing outliers) and three without, to compare performance.
- The datasets with outlier treatment were used to evaluate the model's robustness against extreme values.

### 3. Feature Engineering:
- Engineered features such as `room type`, `number of reviews`, and `location-based factors`, which were identified as significant contributors to price variation.
- Applied one-hot encoding to categorical variables for better performance in machine learning algorithms.

### 4. Train-Test Split & Cross-Validation:
- Split data into training (80%) and testing (20%) sets to ensure fair model evaluation.
- Performed cross-validation to assess model performance and generalization across various datasets.

### 5. Model Building:
- Built a regression model to predict homestay prices using Python and Scikit-learn.
- Extracted coefficients and intercepts to interpret the influence of independent variables on pricing.
- Fine-tuned model hyperparameters using grid search to optimize performance.
- Compared results across datasets, ultimately achieving **50.3% accuracy** with the KNN-imputed dataset, without outlier treatment.
- ![image](https://github.com/user-attachments/assets/c9c06a74-15b9-41c9-bb69-10d6d252bb4c)


### 6. Model Evaluation:
- Achieved the highest accuracy with the KNN-imputed dataset, which outperformed other models across multiple validation tests.

## Results & Business Insights

- **Data-Driven Insights**: The model successfully identified the most influential factors on homestay pricing, including location, property type, and number of reviews. These findings can help optimize pricing strategies for Airbnb hosts.
- **Model Accuracy**: Achieved a **50.3% accuracy** with the KNN imputation dataset without outlier treatment, which was the best performing model.
- **Visualization**: Presented results using heatmaps, boxplots, and correlation matrices to help stakeholders understand the impact of various features on pricing. 
- **Leadership & Project Management**: Managed the project end-to-end, from data collection to modeling, analysis, and presentation of results.

## How to Run the Project
Predictive-Modeling-of-Homestay-Prices.ipynb
