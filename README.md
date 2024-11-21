# Crop Yield Prediction Project  

**Project Overview**
  
The Crop Yield Prediction Project aims to predict crop yields based on environmental factors such as temperature, rainfall, and soil quality, as well as agricultural practices like fertilizer use and irrigation. This analysis empowers farmers with actionable insights to optimize farming decisions and improve overall efficiency in agricultural production.  

 **Business Objective**
  
The primary goal of this project is to develop a machine learning model that accurately predicts crop yields using historical agricultural and environmental data. By achieving this, the project aims to:  
- Assist farmers in making data-driven decisions.  
- Optimize resource allocation such as fertilizer and water usage.  
- Improve crop productivity and reduce waste.  
- Address food security challenges by enhancing agricultural planning.
  
---

### Data Analysis and Methodology  

#### Dataset Preparation  
- Historical data on crop yields and environmental conditions is collected, including factors such as temperature, soil moisture, and rainfall patterns.  
- The dataset is cleaned to handle missing values and outliers to ensure reliable analysis.  

#### Feature Engineering  
- Key factors influencing crop yield are identified through exploratory analysis.  
- Categorical data is transformed into numerical formats where applicable to make it compatible with machine learning models.  
<div align="center">
  <img src="https://github.com/Sree191031/Crop_Yeild_Prediction_Project/blob/main/Crop%20Yeild%20Prediction/Images/Features%20Extracted%20via%20Feature%20Selection.png" width="640" height="360" />
</div>

#### Model Selection  
- Machine learning algorithms, including **Decision Trees**, **Random Forests**, and **Linear Regression**, are tested for their effectiveness.  
- Models are evaluated based on accuracy and their relevance to agricultural datasets.  

#### Training and Testing  
- The dataset is split into **training** and **testing subsets** to validate model performance.  
- **Hyperparameter tuning** is conducted to enhance prediction accuracy.  

#### Visualization  
- Visual insights such as yield patterns by region or crop type are created using graphs and heatmaps to aid stakeholders in understanding the data.  
- NDVI (Normalized Difference Vegetation Index) imagery is used to monitor regional crop health.
<div align="center">
  <img src="https://github.com/Sree191031/Crop_Yeild_Prediction_Project/blob/main/Crop%20Yeild%20Prediction/Images/Actual_Predicted%20Values%20Scatter%20Plot.png" width="640" height="360" />
</div>

---
### Key Insights  
- **Seasonal trends** in crop yield enable better planning of sowing and harvesting schedules.  
- **Correlation analysis** reveals the most impactful factors, such as rainfall levels and soil quality.  
- Regional crop health visualized through NDVI imagery provides actionable insights for irrigation and fertilization strategies.  

---
### Business Recommendations  
1. **Enhance Data-Driven Farming**: Provide farmers with real-time recommendations based on model predictions.  
2. **Optimize Resource Utilization**: Reduce costs and environmental impact by aligning fertilizer and water usage with predicted needs.  
3. **Implement Advanced Crop Monitoring**: Use NDVI imagery for proactive crop health monitoring and corrective actions.  
4. **Support Regional Agricultural Policies**: Guide governments and organizations in resource distribution and subsidy allocation using prediction insights.  

---
### Tools and Technologies  
- **Programming Language**: Python  
- **Libraries**: pandas, sklearn, matplotlib, seaborn  
- **Machine Learning Techniques**: Regression models, Decision Trees, Random Forests  
- **Visualization Tools**: Jupyter Notebook, NDVI imagery processing  

--- 


### Results Summary

#### Model Performance

- **Random Forest**: Achieved the highest accuracy in predicting crop yields, outperforming other models due to its ability to handle non-linear relationships and feature interactions.
- **Decision Tree & Linear Regression**: Delivered reasonable accuracy but were less effective than ensemble methods.

#### Feature Importance
Key factors influencing crop yield:
- **Environmental Variables**:
  - Rainfall: The most critical driver of yield variability.
  - Soil quality and moisture: Strongly influenced yields of specific crop types.
- **Agricultural Practices**:
  - Fertilizer usage and irrigation patterns: Major determinants of performance.

#### Predictions and Trends
- **Optimization Opportunities**:
  - Identified regions and conditions where yield could be enhanced through improved resource allocation.
- **Historical Trend Analysis**:
  - Accurately captured historical trends, providing foresight into future yield performance under similar conditions.

#### Evaluation Metrics

| Model                        | R²       | Mean Error          | Absolute Error    |
|------------------------------|----------|---------------------|-------------------|
| **DecisionTreeRegressor**    | 0.9609   | 289,611,907.57      | 6,059.73          |
| GradientBoostingRegressor    | 0.8966   | 766,587,300.79      | 17,828.13         |
| XGBRegressor                 | 0.8653   | 998,146,199.04      | 20,283.23         |
| RandomForestRegressor        | 0.6843   | 2,340,361,523.52    | 32,465.17         |
| MLPRegressor                 | 0.2311   | 5,699,411,261.97    | 52,462.39         |
| SVR                          | -0.1954  | 8,860,718,236.70    | 57,349.23         |
---
### Future Work
- Integration of real-time data for continuous monitoring and prediction.
- Exploration of deep learning methods for further accuracy improvements.
- Collaboration with agricultural experts to refine data inputs and validate findings.
