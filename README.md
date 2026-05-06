Heart Attack Analysis and Prediction
Project Overview
This project focuses on analyzing a medical dataset to identify key factors contributing to heart attacks. Using Python and Jupyter Notebook, I conducted a thorough data exploration and visualization process to extract meaningful clinical insights.
Technical Workflow
• Data Exploration: Utilized head(), tail(), and shape to understand the structure and dimensions of the dataset.
• Data Cleaning: Performed data integrity checks, including identifying and handling missing values using isnull().sum().
• Statistical Analysis: Generated a comprehensive summary of the data using describe() to analyze distributions and outliers.
• Data Visualization:
• Created Histograms to visualize the distribution of medical features (age, cholesterol, etc.).
• Developed a Correlation Heatmap using Seaborn to identify relationships between different biological indicators and the target variable.
Tools & Libraries
• Pandas: For data manipulation and structured analysis.
• NumPy: For mathematical and numerical operations.
• Matplotlib & Seaborn: For advanced data visualization and statistical plotting.

Model Performance & Analysis

I evaluated six machine learning algorithms to determine the most accurate model for predicting heart attack risks. Below are the results based on the final testing:

• Gaussian Naive Bayes (GNB): Achieved the highest accuracy of 92%. It excelled in handling the statistical distribution of medical features.

• Random Forest Classifier: Performed strongly with 85% accuracy, showing the power of ensemble learning.

• Gradient Boosting Classifier: Provided a solid performance of 80%.

• Decision Tree Classifier: Reached an accuracy of 75%.

• K-Neighbors Classifier (KNN): Achieved 61% accuracy.

• Support Vector Classifier (SVC): Resulted in 59% accuracy.

Conclusion

The Gaussian Naive Bayes model is the most effective for this dataset with 92% accuracy. This project demonstrates my ability to clean data, implement multiple ML models, and analyze their performance to find the best predictive solution.

