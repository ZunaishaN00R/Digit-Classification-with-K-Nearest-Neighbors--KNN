# Digit Classification with K-Nearest Neighbors (KNN)
Efficiently classify digits (0 to 9) using the K-Nearest Neighbors (KNN) classifier. Experiment with diverse k values, identifying the optimal k for maximum accuracy. Visualize model performance through a plotted confusion matrix and generate a comprehensive classification report.

# Overview:
This project leverages the digits dataset from sklearn to perform digit classification (0 to 9) using the K-Nearest Neighbors (KNN) classifier. The primary objectives include finding the optimal value of k for maximum accuracy, visualizing model performance through a confusion matrix, and generating a comprehensive classification report.

# Key Steps:
# Dataset Loading:
Loaded the digits dataset, containing images of handwritten digits.
# Data Splitting:
Divided the dataset into training and testing sets for model evaluation.
# Optimal k Determination:
- Utilized GridSearchCV to explore different values of k (1 to 20).
- Identified the optimal k (1) for maximum accuracy.
# Model Training and Evaluation:
- Trained the KNN classifier with the optimal k.
- Evaluated the model's accuracy, achieving an impressive 98%.
# Performance Visualization:
- Plotted a confusion matrix to visually assess model performance.
- Generated a detailed classification report providing insights into precision, recall, and F1-score for each digit class.
# Key Results:
The final KNN model, with an optimal k of 1, demonstrated exceptional accuracy in digit classification. The confusion matrix and classification report offer a nuanced understanding of the model's strengths and weaknesses for each digit class.
