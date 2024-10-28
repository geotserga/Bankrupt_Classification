# Bankrupt_Classification

This project applies supervised learning techniques for predicting company bankruptcy, leveraging a range of classification models and data preprocessing methods. It was developed as part of a coursework assignment for the Applied Informatics postgraduate program, focusing on methods and tools in artificial intelligence.

### Project Overview
This analysis seeks to identify financial indicators predictive of bankruptcy. Using company performance metrics, we classify businesses as either "Healthy" or "Bankrupt." Through various classifiers, this project explores the following:
- **Data Visualization**: Visualizations uncover trends and anomalies, guiding feature selection and model training.
- **Data Preprocessing**: Steps like handling missing values, normalization, and balancing of class distributions enhance model performance.
- **Model Training**: Several machine learning algorithms are tested and evaluated to compare performance across metrics like F1 Score, ROC AUC, and Confusion Matrix.

### Models Implemented
1. Linear Discriminant Analysis (LDA)
2. Logistic Regression (LR)
3. Decision Tree (DT)
4. Random Forest (RF)
5. k-Nearest Neighbors (KNN)
6. Naïve Bayes
7. Support Vector Machine (SVM)
8. Multi-layer Perceptron (MLP)
  
The best-performing models (Gradient Boosting for balanced data and Multi-layer Perceptron for unbalanced data) are statistically validated for reliability.

### Key Features
- **Stratified K-Fold Cross Validation** ensures each fold represents the class distribution accurately, reducing variance in model evaluation.
- **Performance Comparison on Balanced vs. Unbalanced Data**: Models are tested on both balanced and unbalanced datasets to observe the impact on metrics such as AUC and F1 Score.
- **Performance Constraints**: Sensitivity and specificity thresholds guide model selection to prioritize recall for bankrupt cases without sacrificing overall accuracy.

### Results
- Balanced vs. Unbalanced Data: Models trained on balanced data consistently outperformed those trained on unbalanced data, particularly in recall and F1 Score.
- **Best Performing Models**:
  - **Balanced Data**: Gradient Boosting achieved the highest ROC AUC (0.8477), demonstrating strong class separation.
  - **Unbalanced Data**: Multi-Layer Perceptron achieved the best AUC (0.8482) under unbalanced conditions.
- **Model Robustness**: Random Forests and Support Vector Machines displayed robustness to data imbalance but showed improved recall on balanced datasets, confirming the importance of balanced data for accurate bankruptcy prediction.
- **Sensitivity and Specificity Constraints**: Despite the high AUC scores, models struggled to meet the dual performance constraints of detecting at least 60% of bankrupt companies (Sensitivity) and 70% of healthy companies (Specificity). This suggests further optimization or alternative approaches may be necessary to meet specific business requirements. For further insights, please refer to the statistical comparisons and visualizations included in the report.

### Repository Structure
- *Bankrupt_Classification.ipynb*: Jupyter Notebook containing all data processing, training, evaluation, and visualization code.
- *report.pdf*: Comprehensive report detailing the methodology, findings, and statistical analysis.
