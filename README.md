# Adult-Income-Prediction
 I worked through the full process of building an income prediction model using the UCI Adult dataset.
I started by cleaning the data, removing missing and duplicate rows to make sure the dataset was accurate.
After that, I selected important numeric and categorical features such as age, education, hours worked, and occupation.
I learned how to prepare data using pipelines that include imputing, scaling, and one-hot encoding. This was very useful because it made
preprocessing automatic and easy to reuse later.
I trained two models — Logistic Regression as a baseline and a tuned Random Forest model using GridSearchCV.
Although Logistic Regression gave decent accuracy, the Random Forest performed better overall with higher F1 and ROC-AUC scores.
This showed that ensemble methods can capture more complex relationships in the data. The ROC curve and confusion matrix helped me visually
understand model performance and where errors occurred.
From the feature importance analysis, I learned that capital gain, education level, hours worked per week, and occupation were the most influential
factors in predicting income. This makes sense in real life because people with higher education and capital investments usually earn more.
However, I also realized that models should be used carefully. They can support financial decision-making, but they must avoid unfair bias or
over-reliance on automated predictions. Overall, this assignment taught me how to handle data, build reliable models, and interpret results
responsibly — a complete journey from raw data to meaningful insights.
