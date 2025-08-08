# 🦠 COVID-19 Data Analysis and Predictive Modeling
This project leverages the Corona Virus Report dataset from Kaggle to analyze global COVID-19 data and build predictive models that assess and classify the severity of the pandemic across countries and WHO regions.

The dataset provides daily updates on COVID-19 cases, deaths, recoveries, and active cases worldwide.

## 📊 Data Management & Analysis
Used SQL queries to:

- Extract and aggregate key metrics such as total confirmed cases, deaths, and recoveries by country and WHO region.

- Identify countries with the highest recovery rates, confirmed cases, and fatalities.

## 📈 Exploratory Data Analysis (EDA)
- Performed comprehensive EDA to uncover trends and patterns, including:

- Top 10 countries by confirmed cases (highest and lowest)

- Top 10 countries with most deaths and active cases

- Correlation heatmap of critical variables: Deaths, Recovered, Active, and Confirmed cases

## 🤖 Machine Learning Models

- Linear Regression: Predicted confirmed cases based on Deaths, Recovered, Active, and New cases

- Random Forest Classifier:
  Implemented a multi-class classification model to evaluate pandemic severity. The model’s confusion matrix shows strong classification performance across three classes, with 14, 17, and 24 correct predictions respectively, and only 2 misclassifications   in the middle class.

- Clustering: Grouped countries based on pandemic impact using clustering techniques

- Naive Bayes Classifiers:

- Gaussian Naive Bayes:
  Achieved high accuracy (92%) with a confusion matrix indicating 28 true positives, 3 false positives in the first class, and 7 true positives in the second class.

- Bernoulli Naive Bayes:
  While the model correctly predicted 31 cases of the first class, it struggled with the second class, resulting in 7 false negatives and no correct predictions for that class.

## 📉 Visualizations

- Utilized Matplotlib and Seaborn for clear visual representation of data insights and model results.

## 🛠️ Technologies Used

- SQL – data extraction and aggregation

- Python (Pandas) – data processing

- Matplotlib, Seaborn – data visualization

- Scikit-learn – machine learning models

- Jupyter Notebook, Google Colab – development environments

- Dataset Source: Kaggle - https://www.kaggle.com/datasets/imdevskp/corona-virus-report

## 👨‍💻 Author

**Syed Danish Ahmed**

**Aspiring Data Scientist | Computer Engineering Student**

If you find this project valuable, please ⭐ the repository. Your support is greatly appreciated!

