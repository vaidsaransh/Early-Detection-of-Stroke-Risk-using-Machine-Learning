# Early-Detection-of-Stroke-Risk-using-Machine-Learning

# Project Title: Stroke Risk Prediction with Machine Learning

# Project Highlights:

- Dataset preprocessing and feature engineering
- Exploratory data analysis to gain insights into the dataset
- Building and evaluating machine learning models for stroke risk prediction
- Performance comparison of different algorithms
- Implementation of a predictive functionality for new data
- Visualizations to analyze and present the results

# Step-wise explanation

In this Python project, I focused on developing a machine learning model to predict the risk of stroke based on various features. The main goal was to accurately identify individuals who are at higher risk of experiencing a stroke, enabling proactive healthcare interventions.
To begin, I started by preprocessing the data. I utilized the pandas library to read the dataset from a CSV file called 'healthcare.csv'. 

This step involved cleaning the data, transforming columns into appropriate data types, handling missing values, and scaling numerical features. Categorical variables were encoded to ensure compatibility with the machine learning algorithms.

Next, I performed exploratory data analysis to gain insights into the dataset. I employed techniques such as correlation analysis to understand the relationships between different variables. Calculating a correlation matrix helped uncover any significant associations or dependencies among the features.

For model building and evaluation, I trained multiple machine learning models using the processed data. The models I used included Logistic Regression, K-Nearest Neighbors (KNN), Naive Bayes, and Decision Tree (CART). Each model was trained using the training data and evaluated using the validation data to assess their predictive performance.

To measure the models' accuracy, I calculated the accuracy scores and employed classification summaries, confusion matrices, ROC curves, and AUC scores. These metrics provided a comprehensive evaluation of the models and facilitated a comparison of their performance.

The ultimate aim of the project was to create a predictive functionality that could be applied to new data. For instance, given an individual's age and BMI, the trained models could predict the likelihood of that person experiencing a stroke, providing valuable insights for healthcare professionals.

Throughout the project, I utilized various visualizations to analyze and present the results. These visualizations included scatter plots, regression plots, bar graphs comparing model accuracies, and ROC curves. Visualizations enhanced the interpretability of the findings and facilitated effective communication of the project outcomes.

Overall, this machine learning project focused on accurately predicting stroke risk using a range of models and evaluating their performance. The project's outcomes can potentially contribute to proactive healthcare interventions and improve patient outcomes by identifying individuals at higher risk of stroke.
