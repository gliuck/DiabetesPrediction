# MACHINE LEARNING DIABETES PREDICTION  📊 

## Introduction 📝
This project focuses on predicting diabetes using machine learning techniques. The dataset includes various health and demographic attributes, which are used to predict whether an individual is diabetic.

## Task  🎯 
The primary task is to build a predictive model that determines if an individual has diabetes based on features such as age, sex, cholesterol level, BMI, smoking habits, and more.

## Dataset  📁 
The dataset contains the following columns:
- **Age**: Age of the individual.
- **Sex**: Gender of the individual.
- **HighChol**: Indicator if the individual has high cholesterol.
- **CholCheck**: Indicator if the individual had a cholesterol check in the past five years.
- **BMI**: Body Mass Index.
- **Smoker**: Indicator if the individual is a smoker.
- **HeartDiseaseorAttack**: Indicator if the individual has had a heart disease or attack.
- **PhysActivity**: Indicator if the individual engages in physical activity.
- **Fruits**: Indicator if the individual consumes fruits regularly.
- **Veggies**: Indicator if the individual consumes vegetables regularly.
- **HvyAlcoholConsump**: Indicator if the individual is a heavy alcohol consumer.
- **GenHlth**: General health indicator.
- **MentHlth**: Mental health indicator.
- **PhysHlth**: Physical health indicator.
- **DiffWalk**: Indicator if the individual has difficulty walking.
- **Stroke**: Indicator if the individual has had a stroke.
- **HighBP**: Indicator if the individual has high blood pressure.
- **Diabetes**: The target variable indicating if the individual has diabetes.

## Models Used  🧠 
In this project, four different models were implemented:
1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Support Vector Machine (SVM)**
4. **Neural Network (NN)**

## Exploratory Data Analysis (EDA)  📊 
EDA was conducted to understand the distribution of the features and identify any correlations or patterns. Visualizations were created using `Matplotlib` and `Seaborn`.

## Performance Metrics  📈 
The following metrics were used to evaluate the performance of the models:
- **Accuracy Score**
- **F1 Score**
- **Confusion Matrix**

## Conclusion ✅ 
The results indicate that the models achieved different levels of accuracy and F1 scores. However, there is room for improvement, particularly in the fine-tuning of the model's hyper-parameters.

## Libraries Used  📚 
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `pickle`

## Future Work
Potential improvements could include experimenting with different models such as Random Forests or Gradient Boosting, and applying techniques like cross-validation and hyperparameter optimization.

## Credits  
The dataset used in this project was obtained from [Kaggle](https://www.kaggle.com/datasets/prosperchuks/health-dataset/data?select=diabetes_data.csv). 
