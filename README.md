# Credit-Card-Fraud-Detection-Using-Machine-Learning-Tools


1. Introduction
   
With the rapid development of digitization and information technology, credit cards have become the predominant payment method. However, the surge in online transactions, especially during the Covid-19 pandemic, has led to an increase in credit card fraud. This poses a significant challenge for individuals, financial institutions, cybersecurity, and the government. In this project, we aim to address credit card fraud using data science methodologies to build predictive models for more efficient detection.

2. Related Work
   
Previous studies, such as Awoye’mi et al. (2017) and Maniraj et al. (2019), have explored credit card fraud detection using machine learning techniques. Awoye’mi et al. employed native Bayes, K-nearest Neighbor, and logistic regression, achieving the best accuracy with K-nearest Neighbor. Maniraj et al. focused on minimizing inappropriate fraud classification and achieved over 99.6% accuracy using anomaly detection algorithms.


3. Problem Definition and Algorithm
   
3.1 Task Definition

Credit card fraud involves the unauthorized use of credit or debit cards to fraudulently obtain money or property. We utilized a dataset containing credit card transactions to predict and detect fraudulent activities. The dataset is highly unbalanced, with only 0.172% of transactions labeled as fraud.

3.2 Algorithm Definition

Our approach involves:

Data cleaning: Using under-sampling techniques to address class imbalance.
Exploratory data analysis: Visualizing correlations between principal components obtained through PCA transformation.
Preprocessing data for modeling.
Building models: Employing classifiers like Logistic Regression, K Nearest Neighbors, Support Vector Classifiers, Random Forests, and Neural Networks.
Evaluating performance: Assessing models based on accuracy and recall.


4. Experimental Evaluation
   
4.1 Methodology

We applied both under-sampling and oversampling techniques, using classifiers like Logistic Regression, K Nearest Neighbors, Support Vector Classifier, and Random Forest Classifier. Evaluation metrics included precision, recall, f1-score, and accuracy.

4.2 Results and Discussion

Logistic Regression and Random Forest Classifiers achieved the highest accuracy (95%), with Logistic Regression having the highest ROC score (0.98). Logistic Regression performed exceptionally well in recall for fraudulent transactions. Neural Networks were also explored, with the oversampled dataset showing higher accuracy but lower recall compared to the undersampled dataset.

![image](https://github.com/user-attachments/assets/ac47fd5d-3666-47e9-8eb7-1f40bf0f5c44)


Figure 1: Bar chart showing the unbalanced dataset (left) and the balanced dataset after under-sampling (right).

![image](https://github.com/user-attachments/assets/1abd046c-433f-41b2-8b50-26b727cb41f9)


Figure 2: Confusion matrix of Logistic regression on oversampled vs other classifiers on the under-sampled dataset.

![image](https://github.com/user-attachments/assets/2e561dbe-543e-4971-84f3-94fef015b1d7)


Figure 3: Confusion matrix on a neural network model fitted on the under-sampled dataset.

![Uploading image.png…]()


Figure 4: Confusion matrix on a neural network model fitted on the over-sampled dataset.


5. Future Work
   
Addressing outliers to enhance model accuracy.
Evaluating classifiers on oversampled datasets with higher computing power.
Improving Neural Network models for better fraud prediction.

6. Conclusion
   
The Logistic Regression model demonstrated superior performance in detecting credit card fraud. It outperformed other classifiers, especially in recall for fraudulent transactions. Neural Networks on the undersampled dataset showed promising results, emphasizing the potential for effective fraud detection. These findings can benefit fraud detection agencies in mitigating credit card fraud.
