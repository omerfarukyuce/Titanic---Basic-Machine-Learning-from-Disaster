# 🚢 Titanic Survival Prediction

## 📖 Description
This project is developed to predict survival using the Titanic passenger data. It demonstrates how machine learning techniques can be applied in practice, based on the data of passengers who survived and those who perished in the tragic sinking of the Titanic.

The project includes the following steps:

1. **Data Loading**: Titanic passenger data is loaded from two separate files as training and test sets. Additionally, a file for gender predictions is included.

2. **Data Examination**: The general status, statistics, and missing values of the loaded data are examined. This step is crucial for assessing the quality of the data and its suitability for modeling.

3. **Handling Missing Values**: Missing values in the data are processed using appropriate methods (e.g., filling with the median). This is important for improving the accuracy of the model.

4. **Feature Selection**: Unnecessary or irrelevant columns (e.g., name, ticket number) are removed from the data to enhance the model's performance.

5. **Feature Transformation**: Categorical data (e.g., gender) is converted into numerical format so that the model can understand it.

6. **Model Building**: Various machine learning algorithms (Decision Trees, Random Forests, XGBoost, and Logistic Regression) are used to train the model. The performance of each model is evaluated.

7. **Results Visualization**: The correlations in the data are visualized using a heatmap, analyzing which features have a greater impact on survival.

This project serves as an excellent example for those looking to gain practical experience in data science and machine learning. The Titanic dataset is a perfect starting point for understanding how machine learning techniques can be used to solve real-world problems.

## 🛠️ Libraries Used
- `pandas`: For data analysis and manipulation
- `numpy`: For numerical computations
- `matplotlib`: For data visualization
- `seaborn`: For advanced visualization
- `scikit-learn`: For machine learning algorithms
- `xgboost`: For the XGBoost algorithm
- `graphviz`: For visualizing decision trees

## 📊 Project Steps
1. **Data Loading**: Loading training, test, and gender prediction files.
2. **Data Examination**: Checking the general status and statistics of the data.
3. **Handling Missing Values**: Processing missing values with the median.
4. **Feature Selection**: Removing unnecessary columns.
5. **Feature Transformation**: Converting categorical data into numerical data.
6. **Model Building**: Training different machine learning models.
7. **Results Visualization**: Visualizing the correlation heatmap.

## 📄 License
This project is licensed under the MIT License. For more information, check the [LICENSE](LICENSE) file.
