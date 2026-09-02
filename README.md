# Analyzing-Electricity-Consumption-Patterns-
A big data analytics and machine learning project analyzing London household smart meter consumption patterns using Apache Spark (PySpark) and comparative regression models (Linear Regression, Random Forest, GBT) to support sustainable energy management (SDG7).
Smart Meter Electricity Consumption Analysis & Forecasting
A scalable big data analytics project investigating household electricity consumption patterns and implementing predictive machine learning models using Apache Spark (PySpark) to support energy efficiency and Sustainable Development Goal 7 (SDG7).

Tech Stack and Tools
Big Data Engine: Apache Spark, PySpark MLLib

Programming Language: Python

Data Processing and Analysis: Pandas, NumPy, Matplotlib

Machine Learning Models: Linear Regression, Random Forest Regressor, Gradient Boosted Trees (GBT) Regressor

Core Concepts: Time-Series Forecasting, Exploratory Data Analysis (EDA), Scalable Data Pipelines, Energy Analytics

Project Overview and Objectives
Urban population growth and rising electricity demand necessitate smarter energy management solutions. This project leverages the London Smart Meters Dataset (containing high-resolution records from approximately 5,500 households at 30-minute intervals) to:

Process and analyze large-scale energy datasets efficiently using distributed big data frameworks.

Conduct Exploratory Data Analysis (EDA) to uncover daily, monthly, and seasonal consumption trends and peak demand periods.

Build and evaluate comparative regression models to predict household electricity consumption.

Key Findings and Exploratory Data Analysis (EDA)
Daily Trends: Energy consumption drops significantly during early morning hours (3:00 AM – 5:00 AM) and peaks heavily in the evening (7:00 PM – 8:00 PM).

Seasonal Trends: Higher average consumption is observed during winter months (January, February, December) compared to summer months (July, August).

Feature Importance: Feature importance analysis via the GBT model confirmed that Hour and Month are the dominant predictors of electricity usage.

Model Performance Comparison
Three regression models were implemented using a representative sample of the dataset and evaluated using RMSE, MAE, and R² metrics:

Linear Regression: RMSE: 0.291 | MAE: 0.1686 | R²: 0.031

Random Forest Regressor: RMSE: 0.289 | MAE: 0.1669 | R²: 0.047

Gradient Boosted Trees (GBT): RMSE: 0.287 | MAE: 0.1651 | R²: 0.056

Best Performer: The Gradient Boosted Trees (GBT) model achieved the best performance with the lowest prediction error and highest variance explanation score, successfully capturing non-linear consumption patterns.
