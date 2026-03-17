# Student Performance Prediction

## Overview

This project develops a machine learning pipeline to predict student performance (Pass/Fail) using academic, behavioral, and lifestyle features. The objective is to identify key factors influencing outcomes and support early intervention strategies.

## Methodology

The workflow follows a structured approach, including data cleaning, preprocessing, and exploratory data analysis to understand feature relationships. Feature engineering techniques such as encoding and imputation are applied before training models. Two gradient boosting algorithms are used and optimized through hyperparameter tuning, with performance evaluated using metrics such as accuracy, F1-score, and ROC-AUC.

## Models

The project compares two models:

* XGBoost
* LightGBM

Both are well-suited for structured data and provide strong predictive performance.

## Results

Both models achieved reliable results. XGBoost offered more stable and interpretable outcomes after tuning, while LightGBM provided faster training with competitive accuracy.

## Key Insights

The analysis shows that student performance is strongly influenced by study consistency and behavioral patterns. Lifestyle factors, including sleep and screen time, also contribute significantly to predictions.

## Technical Stack

The implementation uses Python with standard data science libraries, including Pandas, NumPy, Scikit-learn, XGBoost, LightGBM, Matplotlib, and Seaborn.

## How to Run

Clone the repository, install the dependencies listed in `requirements.txt`, and run the Jupyter notebook to reproduce the results.

## Project Structure

The repository includes the main notebook, the requirements file, and optional folders for datasets and visual outputs.

## Limitations and Future Work

The dataset does not capture external influences such as socio-economic factors, which may affect performance. Future work may include incorporating additional features, applying explainability techniques, and deploying the model for practical use.

## Conclusion

This project demonstrates the effectiveness of machine learning in predicting student outcomes and highlights its potential as a tool for supporting data-driven decision-making in education.
