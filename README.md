<h1 align="center">Optimizing Fetal Health Classification with PCA and SMOTE Techniques<h1></h1>

👉 This work focuses on improving fetal health prediction accuracy using machine learning by handling data imbalance and feature optimization.
<br>
<h2>1. Introduction</h2>

In this section, we explain the importance of fetal health monitoring during pregnancy.

Cardiotocography (CTG) is used to monitor fetal heart rate and uterine contractions

Manual interpretation of CTG data can be inconsistent and error-prone

Machine learning helps in early detection of fetal distress

The goal is to assist doctors with accurate, data-driven predictions

📌 This section sets the motivation and problem statement.

<h2>2. Related Work</h2>

Here, we reviewed existing research on fetal health classification.

Previous studies used models like Decision Tree, Random Forest, SVM, ANN

Many achieved good accuracy but faced issues like:

Data imbalance

Overfitting

Poor interpretability

Literature showed Random Forest consistently performs well for CTG data

📌 This helped us choose suitable models and techniques.

<h2>3. Materials and Methods</h2>
A. Dataset

We used a publicly available CTG dataset from Kaggle.

Total records: 2126

Classes:

Normal

Suspect

Pathological

Dataset was imbalanced

Split:

70% training

30% testing

📌 Imbalance was a major challenge.

B. Models Used

We applied multiple machine learning models for comparison.

Random Forest

Decision Tree

K-Nearest Neighbors (KNN)

Logistic Regression

📌 This helped us evaluate which model performs best.

C. Classification Metrics

We evaluated performance using standard metrics.

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

📌 These metrics give a complete picture beyond just accuracy.

D. SMOTE (Synthetic Minority Oversampling Technique)

SMOTE was used to handle class imbalance.

It generates synthetic samples for minority classes

Prevents model bias toward majority class

Improves overall prediction reliability

📌 This significantly improved model performance.

<h2>4. Principal Component Analysis (PCA)</h2>

PCA was used for dimensionality reduction.

Reduces number of features while retaining important information

Helps in:

Reducing noise

Improving efficiency

PCA was applied mainly to KNN and Logistic Regression

📌 Tree-based models like Random Forest don’t require PCA.

<h2>5. Discussion (Results)</h2>
Random Forest

Best performing model

Accuracy: ~98%

Very high precision and recall

Handles high-dimensional data well

Decision Tree

Good interpretability

Slightly lower accuracy than Random Forest

KNN

Performance affected by dimensionality

Improved after PCA

Logistic Regression

Simple and effective

Performed well after PCA

📌 Random Forest outperformed all others.

<h2>6. Limitations</h2>

We also discussed limitations honestly.

Data quality issues affect performance

Limited dataset size

False positives and false negatives

Complex relationship between CTG features and fetal health

📌 This shows research maturity.

<h2>7. Conclusion</h2>

We successfully improved fetal health classification.

SMOTE handled imbalance

PCA reduced dimensionality

Random Forest achieved best results

Model can assist in early detection of fetal distress

📌 The approach improves reliability and accuracy.

<h2>8. Future Scope</h2>

We suggested future improvements.

Use of IoT and wearable devices for real-time monitoring

Integration with AI-driven healthcare systems

Personalized pregnancy monitoring

Deployment in low-resource regions

📌 Shows real-world impact.

<br>
<h2 align="center">“Overall, my research focuses on improving fetal health prediction using machine learning by addressing real-world challenges like data imbalance and feature complexity, with Random Forest showing the best performance.”</h2>
