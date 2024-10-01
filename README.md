# Predictive-Modeling-of-Homestay-Prices



## Objective
Developed a predictive regression model to determine homestay prices for Airbnb properties, aiming to uncover key pricing factors and provide actionable business insights for more effective decision-making.

## Tools & Technologies
- **Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib
- **Tools**: Jupyter Notebook, Power BI, Excel
- **Databases**: MySQL
- **Techniques**: Data Cleaning, KNN Imputation, Outlier Detection (IQR), Regression Analysis, Data Visualization

## Project Overview
This project leverages Airbnb dataset to predict homestay prices using multiple data science techniques. By conducting an exploratory data analysis (EDA) and applying regression models, we aimed to identify key pricing drivers and generate business insights for market strategies.

## Methodology
### 1. Data Understanding & Cleaning:
- Loaded the dataset into Python using Pandas for initial inspection.
- Identified missing values and applied imputation techniques:
  - Mean and Median imputation.
  - K-Nearest Neighbors (KNN) imputation to predict and fill missing values.

### 2. Outlier Treatment:
- Detected outliers using Interquartile Range (IQR) and Boxplot analysis.
- Created three datasets with and three without outlier treatment to evaluate model performance.

### 3. Train-Test Split:
- Split the data into training and test sets using multiple datasets for cross-validation.
- Evaluated model performance across the six datasets.

### 4. Regression Model:
- Built regression models to predict homestay prices and extracted coefficients and intercepts.
- Analyzed the impact of key features on pricing dynamics.

### 5. Model Evaluation:
- Achieved **50.3% accuracy** using the KNN-imputed dataset without outlier treatment, outperforming other models across all datasets.

## Results & Insights
- **Business Insights**: Identified critical factors driving Airbnb homestay pricing, helping optimize pricing strategies.
- **Data Visualization**: Communicated results through clear heatmaps, boxplots, and correlation matrices.
- **Project Impact**: Demonstrated the power of data-driven decision-making, particularly leveraging KNN-imputed data for optimal accuracy.
- **Leadership**: Independently led the project from data collection to analysis, showcasing strong project management and analytical skills.

## Key Features & Visuals
![Heatmap of Feature Correlations](results/heatmap.png)
![Boxplot of Outliers](results/boxplot.png)

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Airbnb-Price-Prediction-Project.git
