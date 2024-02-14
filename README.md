# Reviews
# Text Classification Project

## Overview
This project focuses on text classification using various machine learning algorithms and techniques. It involves the following key steps:
- Importing necessary libraries and datasets
- Reading and preprocessing the dataset
- Feature extraction using Bag of Words, Bag of N-grams, and TF-IDF
- Encoding categorical variables using OneHotEncoder and LabelEncoder
- Splitting the dataset into training and testing sets
- Building and evaluating machine learning models including Logistic Regression, Gradient Boosting, Random Forest, and Chi-Square
- Comparing the performance of different models based on their accuracy scores

## Installation
To run the code locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/text-classification.git
   cd text-classification
2. Install the required dependencies using pip:
       pip install -r requirements.txt
 3. Run the main script:
      python main.py
## Code Structure
- `main.py`: Main script containing the implementation of text classification algorithms and techniques.
- `requirements.txt`: List of Python dependencies required to run the project.
## Models Compared
The performance of the following machine learning models is compared based on their accuracy scores:

- Logistic Regression
- XGBoost
- Random Forest
- Chi-Square
## The accuracy scores of each model are shown below:

Model	R-squared Score
- Logistic Regression	80.75
- XGBoost	83.21
- Random Forest	79.45
- Chi-Square	75.90
  
 ## Conclusion
  
Based on the evaluation results, the XGBoost model achieved the highest accuracy score among the models compared. However, the choice of the best model may vary depending on the specific requirements and characteristics of the dataset.

Feel free to explore further optimizations and experiment with different models to improve the classification performance.
