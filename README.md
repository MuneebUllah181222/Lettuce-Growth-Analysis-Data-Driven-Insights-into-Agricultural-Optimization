# Lettuce-Growth-Analysis-Data-Driven-Insights-into-Agricultural-Optimization
 ## 📄Project Overview
This project explores how environmental conditions influence the growth of lettuce plants. Using data analytics and machine learning, it identifies the optimal conditions for growth phases, helping to enhance agricultural efficiency and sustainability. By modeling and visualizing factors like temperature, humidity, and soil quality, this analysis provides actionable insights for improving lettuce yields and reducing resource waste.

 ## 📊Dataset Description
The dataset contains observations on various environmental conditions and their impact on lettuce growth over time.

Features Included:
* Plant Identifier (Plant_ID): Unique ID for each plant
* Date: Date of observation
* Temperature (°C): Temperature in degrees Celsius
* Humidity (%): Humidity level in percentage
* Total Dissolved Solids (ppm): Parts per million of dissolved solids
* pH Level: pH measurement of the environment
* Growth Days: Days from initial growth to full maturity

## 🚀 Project Steps
1. Data Cleaning & Preprocessing
Missing Values: Handled missing values and outliers to ensure accurate analysis.
Feature Engineering: Created new features like Growth Phase to categorize the plant’s life stages.
2. Exploratory Data Analysis (EDA)
Correlation Analysis: Discovered relationships between environmental factors and growth rates.
Growth Phase Analysis: Visualized how factors like temperature and humidity varied across different growth stages.
3. Modeling for Prediction
Models Used: Tested multiple models, including Linear Regression, Decision Tree, and Random Forest.
Best Model: The Random Forest model achieved the highest accuracy for predicting growth days, with temperature, humidity, and TDS identified as the top influential factors.
4. Insights & Visualizations
Feature Importance Plot: Displayed top environmental factors impacting growth days.
Growth Phase Analysis: Box plots showed trends of temperature and humidity across phases.
Prediction vs. Actual Growth: Scatter plot demonstrating model accuracy in predicting growth days.
## 🔑 Key Insights
Environmental Sensitivity: Temperature, humidity, and TDS have the most significant impact on growth days.
Optimized Conditions: Each growth phase (Early, Middle, Full Maturity) showed distinct environmental needs, providing guidance for tailored care at different stages.
Model Success: With 85% prediction accuracy, the Random Forest model can reliably forecast growth time, supporting farmers in planning harvest cycles more effectively.
## 🌍 Project Impact
Understanding the specific environmental needs of lettuce plants can help farmers optimize resources and maximize yield. By providing data-driven insights, this analysis contributes to sustainable farming practices that reduce resource waste, improve crop quality, and adapt to changing climates. This project demonstrates the power of data analytics in agriculture and how machine learning can support food security and environmental sustainability.

## 🛠️ Tech Stack
Languages: Python
Libraries: Pandas, Numpy, Scikit-Learn, Matplotlib, Seaborn
Machine Learning Models: Random Forest, Decision Tree, Linear Regression
## 📈 Sample Visualizations
Feature Importance Plot
## 📈 Sample Visualizations

1. **Feature Importance Plot**
   ![Feature Importance](images/Feature Importance - Gradient Boostin.png)

2. **Growth Phase Box Plot (Temperature)**
   ![Growth Phase Temperature Box Plot](images/Box plot.png)

3. **Prediction vs. Actual Growth Days**
   ![Prediction vs. Actual](images/Gradient Boosting - predictions.png)
   
## 💡 Future Work
Expand to other crops and environmental datasets.
Integrate climate forecasts to predict crop yield under future climate scenarios.
Develop a predictive model for optimal harvest scheduling.
