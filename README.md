# Project Overview

I started by loading my data and then selected the relevant features: **Age** and **EstimatedSalary** to predict **Purchased** (my target variable). I split the data into training and testing sets to evaluate my models effectively.

The dataset I used contains social network ads data that help predict whether a user will purchase a product based on age and estimated salary.

## The Role of Scaling

A key part of my project involved **Standard Scaling** the features. This process transforms the data so that each feature has a mean of 0 and a standard deviation of 1. I visualized the data both before and after scaling to demonstrate this transformation.

## Model Training and Evaluation

I trained and evaluated two different machine learning models:

- **Logistic Regression:** This model is often sensitive to the scale of features. I trained it once on the original data and again on the scaled data.

- **Decision Tree Classifier:** This model is generally not affected by feature scaling, as it makes decisions based on thresholds rather than magnitudes. I also trained this model on both the original and scaled data.

Finally, I compared the accuracy of each model in both scenarios (with and without scaling) to observe the impact of StandardScaler on their performance.

## Tools and Libraries

- Python  
- scikit-learn  
- pandas  
- matplotlib  
- seaborn  

## Results Summary

I found that Logistic Regression’s performance improved after scaling, while the Decision Tree Classifier’s accuracy remained largely unchanged, as expected.

## How to Run

1. Clone the repository.  
2. Install the required libraries (listed above).  
3. Run the Jupyter notebook/script to see the full analysis and results.

## Next Steps

To further improve this project, I could experiment with more features, try other scaling techniques, or test additional machine learning models like SVM or Random Forest.

