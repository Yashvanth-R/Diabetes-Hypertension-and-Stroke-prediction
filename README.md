# Diabetes-Hypertension-and-Stroke-prediction

Diabetes is an illness where a body cannot produce or effectively use insulin, leading to elevated blood sugar levels. The signs include increased thirst, frequent urination, and weight loss. Complications can include heart disease, nerve damage, and vision loss. Insulin is a hormone that regulates blood sugar.
Stroke occurs when blood supply to the brain is interrupted, either by a blood clot or a burst blood artery, a stroke results.

Symptoms include sudden weakness or numbness, difficulty speaking and severe headache. Strokes can cause permanent brain damage and disability or death. The rupture or blockage prevents blood and oxygen from reaching the brain’s tissues. According to the Centers for Disease Control and Prevention (CDC), stroke is the fifth-leading cause of death in the United States.
In hypertension, often known as high blood pressure, the pressure of the blood in the arteries is abnormally high. This puts strain on the heart and blood vessels, leading to heart disease, kidney disease, and stroke. It is often symptomless but can be detected through regular blood pressure checks. 
It can be managed through lifestyle changes such as diet, exercise, and stress reduction, and medication may be necessary in severe cases. These chronic diseases can lead to serious complications and disabilities, making early detection and prediction essential for effective treatment and management.

Diabetes, hypertension, and stroke are significant health concerns worldwide, contributing to a substantial burden on individuals, families, and healthcare systems. Early detection and prediction of these conditions play a crucial role in preventing complications, improving patient outcomes, and reducing healthcare costs. Computational algorithms have emerged as valuable tools in predicting and managing these chronic diseases.

----------------------------------------------------------------------------------------------------------------------------------------------

## Methodology

1. Data source:
The diabetes dataset used in this research was procure from the center for disease control and prevention BRFSS (2015). It contains medical records for over 70,000 individuals with type 2 diabetes, including demographic information, medical history, and various health measurements such as blood pressure and physical activity.

2. Data preprocessing:
The data was first pre-processed to remove any missing values, outliers, and irrelevant information. Next, the data was normalized to ensure that all features were on a similar scale. In addition, data was split into training (80%) and testing (20%) sets, to estimate the performance of the models.

3. <img width="321" alt="Picture1" src="https://github.com/user-attachments/assets/97293256-642b-4196-a1cd-7d4530605a1d" />

4.  Feature Selection:
To select the features for the ML models, we used a combination of feature importance and correlation analysis. The feature importance was calculated using the Principal Component Analysis (PCA), and the features with a high feature importance score were selected for the study. The correlation analysis was performed to remove any highly correlated features, as these can lead to multicollinearity issues in the models.

5.  Model Selection:
We used twelve classification algorithms in this study: logistic regression, support vector machines (SVM), K Neighbors Classifier(metric="euclidean"), Gaussian NB, Decision Tree Classifier, Random Forest Classifier, Gradient Boosting Classifier, AdaBoost Classifier . The above-mentioned algorithms were chosen because they are commonly used for binary classification tasks and have been shown to perform well on medical datasets. We implemented the algorithms using the scikit-learn library in Python and tuned the hyperparameters using k-fold cross-validation on the training data.

6.  Evaluation Metrics:
The performance of these models was estimated using a set of common evaluation metrics, including accuracy and recall. The accuracy was well calculated as the proportion of correctly predicted outcomes of the total number of predictions. Recall is a measure of how many actual positive cases were correctly recognized by the model. It answers the question, "Out of all the actual positive cases, how many did the model correctly identify?"

---------------------------------------------------------------------------------------------------------------------------------

## Results

The results of our study showed that all the classification algorithms used performed moderately well on the diabetes dataset, with mean accuracy scores ranging from 56% to  74%. The gradient boosting algorithm had the highest mean accuracy score (75.5%), followed by the AdaBoost classifier (75%) and the rbf SVM (74.9%). The below table represents the accuracy of all the machine learning algorithms- The gradient boosting algorithm had the highest mean accuracy score of 75.54%.

With regards to stroke prediction, the results indicated that gender has no effect on the risk of stroke. However, the results revealed that certain factors such as smoking, hypertension, and heart disease increase the risk of stroke. The results also showed that people whose type of work is "self-employed" have a higher risk of stroke than other types of work. There was no clear connection between residence type and stroke, but there was a slight tendency towards stroke in a rural residence type.

The results of our study come up with the understanding of the diabetes, stroke and hypertension prediction using machine learning models. The high mean accuracy scores of the gradient boosting algorithm and the AdaBoost classifier indicate that these algorithms may be effective in predicting diabetes. Additionally, the results highlighting the impact of risk factors such as smoking, hypertension, and heart disease on stroke risk are valuable for developing preventive measures. Overall, the results of this study give the important insights of the prediction on the diabetes, stroke, hypertension and highlight the potential for using machine learning algorithms in this field. 





