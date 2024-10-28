# Bankrupt_Classification

This project applies supervised learning techniques for predicting company bankruptcy, leveraging a range of classification models and data preprocessing methods. It was developed as part of a coursework assignment for the Applied Informatics postgraduate program, focusing on methods and tools in artificial intelligence.

### Project Overview
This analysis seeks to identify financial indicators predictive of bankruptcy. Using company performance metrics, we classify businesses as either "Healthy" or "Bankrupt." Through various classifiers, this project explores the following:
⋅⋅* **Data Visualization**: Visualizations uncover trends and anomalies, guiding feature selection and model training.
⋅⋅* **Data Preprocessing**: Steps like handling missing values, normalization, and balancing of class distributions enhance model performance.
⋅⋅* **Model Training**: Several machine learning algorithms are tested and evaluated to compare performance across metrics like F1 Score, ROC AUC, and Confusion Matrix.

### Models Implemented
- Linear Discriminant Analysis (LDA)
- Logistic Regression (LR)
- Decision Tree (DT)
- Random Forest (RF)
- k-Nearest Neighbors (KNN)
- Naïve Bayes
- Support Vector Machine (SVM)
- Multi-layer Perceptron (MLP)
  
The best-performing models (Gradient Boosting for balanced data and Multi-layer Perceptron for unbalanced data) are statistically validated for reliability.

### Key Features
Stratified K-Fold Cross Validation ensures each fold represents the class distribution accurately, reducing variance in model evaluation.
Performance Comparison on Balanced vs. Unbalanced Data: Models are tested on both balanced and unbalanced datasets to observe the impact on metrics such as AUC and F1 Score.
Performance Constraints: Sensitivity and specificity thresholds guide model selection to prioritize recall for bankrupt cases without sacrificing overall accuracy.

### Results
The project concludes that data balance significantly improves model accuracy and robustness, particularly for models like Random Forests and Support Vector Machines. For further insights, please refer to the statistical comparisons and visualizations included in the report.

### Repository Structure
Bankrupt_Classification.ipynb: Jupyter Notebook containing all data processing, training, evaluation, and visualization code.
report.pdf: Comprehensive report detailing the methodology, findings, and statistical analysis.

### Acknowledgments
This project was conducted as part of the Artificial Intelligence course in the Applied Informatics MSc program. Special thanks to my instructors for their guidance.
