# Electrical-Fault-detection-With-SVM-and-Logistic-regression
Electrical Fault detection With SVM and Logistic regression

This project aims to detect electrical faults in power systems using machine learning algorithms such as Logistic Regression and Support Vector Machines (SVM). The dataset used in this project is obtained from Kaggle and contains over 7,861 labeled data points, including measurements of Line Voltages and Line Currents.

## Project Description

The project involves data collection, analysis, cleaning, and modeling using Python. The dataset is analyzed to detect any fluctuations in voltage or current that indicate a fault. The predicted symmetrical and sinusoidal behavior with a 120-degree phase shift in both current and voltage is seen in the current and voltage graphs under the "not Faulty" condition. However, noticeable aberrations may be seen on the voltage and current curves when the system is experiencing a "Faulty" condition.

Two machine learning algorithms, Logistic Regression and SVM, are used to train the model. Both models are chosen for their proven efficacy in binary classification tasks like fault detection. Preprocessing steps involved handling missing values and standardizing features. During training, varied hyperparameters were explored for both models.

## Installation

To install and run the project locally, follow these steps:

1. Clone the repository: git clone https://github.com/username/electrical-fault-detection.git
2. Install required dependencies: pip install -r requirements.txt
3. Run the project: python app.py

## Usage

The project provides a trained machine learning model that can detect electrical faults in power systems. The input to the model is a set of measurements of Line Voltages and Line Currents, and the output is a binary digit sequence that corresponds to specific fault types occurring within the system involving four components. When all four digits are 0, it indicates a normal operating condition with no faults detected.

## Results

The results for both models are summarized in Table 1:

| Model | Training accuracy (%) | Model accuracy score (%) |
|-------|------------------------|--------------------------|
| Logistic regression | 90.19 | 89.57 |
| SVM | 100 | 79.53 |

The comparative analysis between Logistic Regression and SVM models revealed that logistic regression performing well with big data with 90.19% training accuracy and 89.57% for model accuracy score. On the other hand, SVM with kernel RBF with c = 10 and sigma = 0.1 showing training accuracy of 100% but model accuracy of 79.53%.

## Conclusion

The project highlights the importance of machine learning models in analyzing faults in power systems. It provides valuable information on predicting faults, ensuring system dependability, and implementing actions to mitigate faults. Future work could explore ensemble methods or neural network architectures to further improve fault prediction accuracy.

## References

1. Vishal, M., Kamal, A. and Viji, D., 2023, June. Electrical fault detection using machine learning algorithm. In AIP Conference Proceedings (Vol. 2782, No. 1). AIP Publishing.
2. Kim, M.C., Lee, J.H., Wang, D.H. and Lee, I.S., 2023. Induction Motor Fault Diagnosis Using Support Vector Machine, Neural Networks, and Boosting Methods. Sensors, 23(5), p.2585.
3. https://www.javatpoint.com/logistic-regression-in-machine-learning
4. https://www.geeksforgeeks.org/introduction-to-support-vector-machines-svm/
5. Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow" by Aurélien Géron
6. Introduction to Machine Learning with Python: A Guide for Data Scientists" by Andreas C. Müller and Sarah Guido
7. Electric Power Systems: A Conceptual Introduction" by Alexandra von Meier
8. Machine Learning: A Probabilistic Perspective" by Kevin P. Murphy.
9. Simon Hayekins, Neural Networks: A comprehensive foundation,
