# Diabetes Classifier

This project uses gathered data and machine learning techniques to classify diabetes based on various features. The goal is to develop an accurate model that can predict whether an individual has diabetes or not.

## Project Rundown

1. **Exploratory Data Analysis (EDA)**
   - Performed data visualization and cleaning to prepare the data for machine learning.
   - Analyzed the distribution of features and their relationships with the target variable.

2. **Feature Importance**
   - Applied Random Forest and Decision Tree models to determine the most important features for diabetes classification.
   - Identified hemoglobin level and glucose level as the top two features contributing to diabetes prediction.

3. **Model Exploration**
   - Initially used Random Forest and Decision Tree models, but they showed poor performance in terms of recall and precision.
   - Explored alternative models, including scenarios where hemoglobin level or glucose level might not be available.
   - Discovered that other models were underfitting and not complex enough for this problem.

4. **Neural Network Model**
   - Implemented a Neural Network model, which achieved the best performance among all the models tested.
   - The Neural Network model demonstrated high accuracy, precision, and recall scores.
   - Optimized the model's architecture and hyperparameters to enhance its performance.

## Dataset

The dataset used in this project contains various features related to diabetes, including:

- Glucose level
- Blood pressure
- Skin thickness
- Insulin level
- BMI
- Age
- Diabetes pedigree function
- Hemoglobin level

The target variable indicates whether an individual has diabetes or not.

## Results

The Neural Network model achieved the following performance metrics:

- Accuracy: 91%
- Precision: 91%
- Recall: 91%

These results demonstrate the effectiveness of the Neural Network model in classifying diabetes based on the given features.

## Notebook

The complete code and analysis can be found in the following Colab notebook:

[Diabetes Classifier Notebook](https://colab.research.google.com/drive/1_j9-wO6mkPOn_rIP8nBgxAzZMKPK-4Zi?usp=sharing)

Feel free to explore the notebook for a detailed understanding of the project.

## Future Improvements

Some potential areas for future improvements include:

- Collecting more diverse and representative data to enhance the model's generalization ability.
- Exploring advanced feature engineering techniques to create more informative features.
- Experimenting with ensemble methods or other advanced machine learning algorithms.
- Deploying the model as a web application or API for easy access and usage.

##Acknowledgement

All of this was done from scratch. Thank you for Annie Wernerfelt and Silvani Amin for their help in the project. Data science and machine learning skills was taught by Dr. Ryan Marcus and Jacob Gardener.
