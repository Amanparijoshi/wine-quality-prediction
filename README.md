# wine-quality-prediction
Wine quality prediction using physicochemical properties and machine learning models.

Project Overview

This project analyzes physicochemical properties of red wine samples to understand the factors influencing wine quality. The objective is to perform exploratory data analysis, identify key influencing features, and build machine learning models to predict wine quality.

The dataset contains 1599 wine samples with 11 chemical attributes and one quality rating variable.

Dataset Description

Features include:

Fixed Acidity

Volatile Acidity

Citric Acid

Residual Sugar

Chlorides

Free Sulfur Dioxide

Total Sulfur Dioxide

Density

pH

Sulphates

Alcohol

Quality (Target Variable, scale 0–10)

Objectives

Analyze quality distribution.

Study correlation between physicochemical properties and wine quality.

Evaluate impact of alcohol and volatile acidity.

Compare Decision Tree and Random Forest models.

Generate business insights from analysis.

Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-Learn

Decision Tree Classifier

Random Forest Classifier

Exploratory Data Analysis

Most frequent quality rating: 5

Quality range: 3 to 8

Majority wines fall into medium quality range (5–6)

Key Correlations

Alcohol: Strong positive correlation with quality

Volatile Acidity: Moderate negative correlation

Residual Sugar: Weak influence

Sulfur Dioxide: Minimal direct effect

Model Performance
Model	Accuracy
Decision Tree	~56%
Random Forest	~66%

Random Forest outperformed Decision Tree due to ensemble learning and better generalization.

Business Insights

Alcohol content is a strong positive indicator of quality.

Higher volatile acidity reduces wine ratings.

Most wines are average quality, indicating opportunity for premium improvement.

Machine learning can assist in early-stage quality prediction before bottling.

Conclusion

The analysis shows that wine quality is strongly influenced by alcohol levels and acidity balance. Random Forest provides better predictive performance compared to a single Decision Tree model. The results demonstrate how data-driven methods can support quality optimization and improve consistency in wine production.
