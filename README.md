Overview
This project is an end-to-end Car Price Predictor developed as part of the CampusX Machine Learning curriculum. It leverages Linear Regression to build a robust model capable of estimating the selling price of used cars. The aim is to understand the factors influencing car valuations and demonstrate a complete machine learning workflow, from data acquisition and preprocessing to model training, evaluation, and potentially deployment.

Features
Data Acquisition & Cleaning: Handling real-world raw car dataset, addressing missing values, and cleaning inconsistent data.

Exploratory Data Analysis (EDA): In-depth statistical and graphical analysis to uncover patterns, correlations, and insights into factors affecting car prices.

Feature Engineering: Creation of new, more informative features (e.g., Car Age) to enhance model accuracy.

Categorical Feature Handling: Effective encoding of categorical variables (e.g., Fuel_Type, Transmission, Brand) using techniques like One-Hot Encoding.

Numerical Feature Scaling: Standardizing numerical features to ensure all features contribute equally to the model.

Linear Regression Model: Implementation and training of a Multiple Linear Regression model from scikit-learn.

Model Evaluation: Comprehensive assessment of the model's performance using metrics such as R-squared, Mean Absolute Error (MAE), and Mean Squared Error (MSE).


Technologies Used
Python: The primary programming language.

Jupyter Notebook (or Google Colab): For interactive development, analysis, and visualization.

Pandas: For powerful data manipulation and analysis.

NumPy: For fundamental numerical operations.

Scikit-learn: The go-to library for machine learning tasks, including:

LinearRegression for model building.

StandardScaler for feature scaling.

OneHotEncoder for categorical encoding.

train_test_split for data splitting.

r2_score, mean_absolute_error, mean_squared_error for model evaluation.

Matplotlib: For creating static, publication-quality visualizations.

Seaborn: For enhanced statistical data visualizations.

Flask
