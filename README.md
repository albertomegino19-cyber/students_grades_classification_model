Student Performance Prediction
Overview

This project builds a machine learning pipeline to predict whether a student will pass or fail based on academic, behavioral, and lifestyle data. The goal is not only to make accurate predictions, but also to understand which factors drive student performance and could help guide early interventions.

Methodology

The workflow follows a standard data science process: data cleaning, preprocessing, and exploratory analysis to understand patterns and relationships in the data.

Missing values were handled and categorical variables encoded before training the models. Feature engineering was applied where relevant.

Two gradient boosting models were trained and tuned using cross-validation. Performance was evaluated using accuracy, F1-score, and ROC-AUC to ensure a balanced assessment.

Models

The project compares two tree-based ensemble models:

XGBoost

LightGBM

Both are well-suited for tabular data and handle non-linear relationships effectively.

Results

Both models performed well overall.

XGBoost delivered slightly more stable results after tuning and was easier to interpret, while LightGBM trained faster and achieved similar performance levels.

Key Insights

The results suggest that consistency in study habits and behavioral patterns are strong predictors of student performance.

Lifestyle factors such as sleep and screen time also play a relevant role. A feature importance analysis was used to identify which variables contributed most to the model’s predictions.

Technical Stack

Python was used for the full pipeline, including:

Pandas and NumPy for data manipulation

Scikit-learn for preprocessing and evaluation

XGBoost and LightGBM for modeling

Matplotlib and Seaborn for visualization

How to Run

Clone the repository, install the dependencies listed in requirements.txt, and run the Jupyter notebook to reproduce the analysis and results.

Project Structure

The repository contains the main notebook, a requirements file, and optional folders for datasets and generated visualizations.

Conclusion

This project shows how machine learning can be used not only to predict outcomes, but also to better understand the factors behind student performance, with potential applications in education and early intervention strategies.onstrates the effectiveness of machine learning in predicting student outcomes and highlights its potential as a tool for supporting data-driven decision-making in education.
