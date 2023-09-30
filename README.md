# Devanshs_Cardiovascular_Risk_Prediction
![HeartMuscle-625147262-770x533-1](https://github.com/DevanshA2511/Devanshs_Cardiovascular_Risk_Prediction/assets/130047748/9a422206-2654-4406-a5db-14da4274b35e)

Cardiovascular disease stands as a global leading cause of mortality, emphasizing the critical need for early risk prediction to facilitate timely intervention and prevention. Machine learning techniques have emerged as powerful tools in this regard, offering promising outcomes by analyzing an array of risk factors.

The primary objective of this project is to construct a robust machine learning model for forecasting an individual's 10-year cardiovascular disease risk, utilizing a dataset encompassing demographic, clinical, and laboratory data.

The dataset employed is the renowned Framingham Heart Study dataset, a gold standard in cardiovascular risk prediction. It encompasses records of 3,390 participants, meticulously monitored over a decade for cardiovascular events. Among its 17 variables are age, gender, blood pressure, cholesterol levels, smoking habits, and diabetes status.

The project's initial phase involves data preprocessing, entailing the handling of missing values, categorical variable encoding, and numerical variable scaling. Subsequently, the dataset is divided into training and testing sets using a 80:20 ratio.

Various machine learning algorithms are applied to the training data, including logistic regression, KNN, XGBoost, SVC, random forest, and the Naive Bayes Classifier, as they have demonstrated prowess in cardiovascular risk prediction. These algorithms are diligently trained on the training data, with their performance meticulously evaluated on the testing data.

The evaluation encompasses key metrics such as accuracy, precision, recall, and the area under the receiver operating characteristic curve (AUC-ROC), collectively shedding light on the model's performance.

Results indicate that XGBoost excels, boasting an accuracy of 0.89, precision of 0.92, recall of 0.85, and an AUC-ROC of 0.89. This underscores the model's overall proficiency in predicting cardiovascular risk.

Further analysis drills down into the dataset to unearth crucial features. The feature importance analysis reveals that age, education, prevalent hypertension, and daily cigarette consumption hold paramount importance in predicting cardiovascular risk. This insight empowers healthcare professionals to pinpoint high-risk individuals and implement targeted preventive strategies.

In summation, this project underscores the efficacy of machine learning techniques in cardiovascular risk prediction, leveraging the esteemed Framingham Heart Study dataset. The resultant machine learning model can be a valuable tool for healthcare practitioners, aiding in the identification of individuals at elevated risk of cardiovascular disease and enabling proactive risk reduction measures.
