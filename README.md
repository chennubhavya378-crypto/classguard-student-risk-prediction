# classguard-student-risk-prediction
Student Performance Risk Prediction System (ClassGuard) is a machine learning project that predicts student risk (Safe/At Risk) using academic data and Logistic Regression to support early intervention and decision-making.
The Student Performance Risk Prediction System (ClassGuard) is a machine learning-based application developed to identify students who are at risk of poor academic performance. The primary objective of this project is to assist educators and institutions in making informed, data-driven decisions by providing early warnings about students who may require additional academic support.

The system utilizes a structured dataset containing key academic indicators such as attendance percentage, total score, weekly self-study hours, and class participation. A new target variable, risk_label, is created by categorizing students into Safe (grades A and B) and At Risk (grades C, D, and F). This transformation enables the problem to be addressed as a binary classification task.

The project is implemented using Python in a Google Colab environment, leveraging powerful libraries such as Pandas for data manipulation, NumPy for numerical operations, and Scikit-learn for machine learning. A Logistic Regression model is employed due to its simplicity, efficiency, and strong performance in classification tasks. The dataset is split into training and testing sets (70:30 ratio), and the model is evaluated using metrics such as accuracy, precision, recall, and F1-score.

The system demonstrates excellent performance, achieving an accuracy of approximately 99.93%, with minimal misclassification as shown in the confusion matrix. This indicates that the selected features and model are highly effective in predicting student risk.

In addition to the machine learning implementation, the repository also includes user interface designs created using Figma. These designs illustrate how the system can be integrated into a practical application with input forms, result displays, and alert notifications.

Overall, this project highlights the potential of machine learning in the education domain by enabling early identification of at-risk students. The repository is well-structured and includes all necessary components such as dataset, code, outputs, and documentation, making it easy to understand, reproduce, and extend for future enhancements.
