# E-Commerce-Shipping-Data-Analysis-and-Machine-Learning-Project

### Welcome to this project's repository! 🚀

## Project Overview

In this project, we embarked on an exciting journey to uncover valuable insights from the "E-Commerce Shipping Data" of an international e-commerce company specializing in electronic products. The primary objective was to leverage advanced machine learning techniques to study customer behavior and improve the company's shipping processes.

> **Data for this project is picked from a `Kaggle` dataset (Link given) [https://www.kaggle.com/datasets/prachi13/customer-analytics]**

### Key Questions Explored
1. Customer Rating vs. On-Time Delivery:
  * Investigated the relationship between customer ratings and product delivery times.
  * Explored whether high product importance correlated with the highest ratings and on-time deliveries.
2. Shipment Modes Analysis:
  * Analyzed the percentage of shipments delivered on time and those not delivered on time, categorized by different shipment modes.
  * Examined whether the weight of products influenced the choice of delivery mode.
3. Customer Rating's Impact on On-Time Delivery:
  * Explored how customer ratings affected the likelihood of on-time shipment delivery.

### Methodology
To answer these intriguing questions, we followed a rigorous methodology:

#### Data Preprocessing:

Employed preprocessing techniques such as ordinal and one-hot encoding using column transformers to prepare the data for modeling.
Modeling:

Utilized a variety of classification models, including:
- SGDClassifier
- LogisticRegression
- RandomForest
- KNNClassifier
- MLPClassifier
- SVC

#### Model Evaluation and Selection:

Implemented cross-validation with the "f1" score as the scoring metric to identify the most suitable model.

#### Hyperparameter Tuning:

Fine-tuned the selected model's hyperparameters using GridSearchCV for optimal performance.

#### Performance Metrics:

Generated a comprehensive classification report, Confusion Matrix, and various other performance metrics to thoroughly assess the model's capabilities.

#### Testing on Holdout Data:

Applied the best-performing model to the holdout test set, obtaining a final set of metrics to gauge real-world performance.

### Project Structure
This repository is organized as follows:

`e-commerce-shipping.ipynb`: Contains Jupyter notebooks detailing the data analysis and machine learning pipeline.
`Data`: Data for this project is picked from a `Kaggle` dataset (Link given) [https://www.kaggle.com/datasets/prachi13/customer-analytics]

### Short Summary 
*This project addressed critical challenges faced by an international e-commerce company selling electronic products. It entailed exploring the impact of customer ratings on delivery times, analyzing the relationship between product importance and high ratings, and investigating the influence of shipment modes and product weight on on-time deliveries. Through thorough Exploratory Data Analysis (EDA) and machine learning techniques, we revealed crucial insights, selected the optimal predictive model, and offered actionable recommendations for improving the company's operations.*


### Dependencies
To run the code and notebooks in this project, you will need the following dependencies:

Python 3.x
Jupyter Notebook
Libraries: NumPy, pandas, scikit-learn, matplotlib, seaborn, and any other libraries specified in the notebooks.
Contributors
Rahul Gupta

Feedback and Questions
If you have any questions, suggestions, or feedback, please don't hesitate to open an issue or reach out to me on [https://www.linkedin.com/in/rahul-gupta-320349212]. I welcome collaboration and look forward to hearing from you!

Thank you for exploring the E-Commerce Shipping Data Analysis and Machine Learning Project. I hope you find it informative and inspiring for your own data-driven endeavors! 📊🤖📦
