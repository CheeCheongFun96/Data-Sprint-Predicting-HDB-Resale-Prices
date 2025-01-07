HDB Resale Price Prediction using Linear Regression
Project Overview
This project is part of a General Assembly AGILE Data Sprint, where the goal was to analyze housing data and predict HDB resale prices using a linear regression model. The dataset comprises key features of HDB flats in Singapore, such as town, size, floor level, and flat type, to identify factors influencing resale prices.

Through exploratory data analysis (EDA), model building, and fine-tuning, the project achieved a root mean square error (RMSE) of 60K on prices ranging from 165K to 1.18M. The insights and results of this project can support policy makers, real estate professionals, and homebuyers in understanding price dynamics and making informed decisions.

Problem Statement
Singapore's housing market is dynamic and complex, with various factors influencing HDB resale prices. This project aimed to address the following key questions:
What are the most significant factors driving HDB resale prices?
Can a predictive model provide accurate price forecasts to support stakeholders?

Source: Publicly available housing data.
Features:
Town - The area or neighborhood of the HDB flat.
Flat Type - The size of the flat (e.g., 3-room, 4-room, etc.).
Floor Level - Flat’s position in the building (e.g., low, medium, high).
Size (sqft) - The floor area of the flat in square feet.
Resale Price - Resale price of which the flat sold at (the target variable to predict).

The data was cleaned and prepared for analysis, with missing values handled and outliers addressed.

Exploratory Data Analysis (EDA):
Identified correlations between flat attributes and resale prices.
Visualized trends across features like town and flat type.

Model Development:
Built a linear regression model to predict resale prices.
Conducted feature selection to focus on the most impactful variables.

Model Evaluation:
Evaluated performance using RMSE as the key metric.
Fine-tuned the model to achieve better predictions.

Insights Presentation:
Created visualizations to demonstrate the impact of key variables on pricing trends.

Model Performance:
Achieved an RMSE of 60K on HDB resale prices ranging from 165K to 1.18M.

Key Insights:
Flat size and type are among the strongest predictors of resale prices.
Floor level impacts resale prices, with higher floors generally commanding premium prices.
Resale prices vary significantly across towns, highlighting geographical price disparities.

Technologies Used:
Python:
Libraries - Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
Jupyter Notebook (built on Deepnote) - For data exploration, model building, and visualization.

Future Improvements:
Incorporate additional features such as proximity to MRT stations, school ratings, and amenities to improve model accuracy.
Experiment with more advanced regression techniques like Ridge Regression or Random Forest Regressors.
Extend the analysis to predict price trends over time using time series forecasting.

Acknowledgments:
This project was completed as part of General Assembly's AGILE Data Sprint.
Special thanks to the instructors and team members for their guidance and collaboration.
