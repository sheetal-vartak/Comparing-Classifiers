# Comparing-Classifiers
In this third practical application assignment, the goal is to compare the performance of the classifiers (k-nearest neighbors, logistic regression, decision trees, and support vector machines). The dataset is related to the marketing of bank products over the telephone.

# Data
The dataset you will use comes from the [UC Irvine Machine Learning Repository] (https://archive.ics.uci.edu/ml/datasets/bank+marketing). The data is from a Portuguese banking institution and is a collection of the results of multiple marketing campaign

# Jupyter Notebook
https://github.com/sheetal-vartak/Comparing-Classifiers/blob/main/prompt_III.ipynb

# Summary and Findings

## Statistical Insights

1. Subscription Distribution Imbalance:

    Only 12.7% of contacts result in subscriptions, creating a highly imbalanced dataset (30k entries post cleaning). Please see the barplot above.
2. Data Quality Issues:

    Very high rate of unknown values in the data set.
3. Demographic Patterns:

    a. Students and retired individuals show highest conversion rates

    b. University degree holders demonstrate higher subscription propensity
   
    c. Management and admin roles are well-represented but show moderate conversion
5. Financial Status Patterns:

    a. Clients without personal loans show higher subscription rates
   
    b. Housing loan status shows less clear correlation
   
    c. Financial stability appears to influence term deposit interest

## Model Performance Analysis

### Machine Learning Results

     1. Baseline Performance: 88.7% (always predicting "no subscription")

     2. Best Model: Tuned Logistic Regression achieving ~87% accuracy

     3. Model Comparison:
        a. Logistic Regression: strong baseline performance, quite fast

        b. Decision Trees: Moderate performance, quite fast
      
        c. KNN: moderate performance, pretty fast

        d. SVM: Longest training time, competitive performance

### Key Performance Insights

      1. Hyperparameter tuning provided modest but consistent improvements across models

### Actionable Business Insights

      1. Target Customer Segments

        a. Students: Highest conversion rates, likely due to lower financial commitments
        b. Retired individuals: Strong interest in stable investments
        c. University graduates: Higher financial literacy and investment awareness
        d. Clients without personal loans: Better financial position for additional investments

      2. Marketing Strategy Optimization

        a. Focus on education level: University degree holders show 15-20% higher conversion
        b. Consider age segmentation: Different messaging for students vs. retirees
        
      3. Cost-Benefit Analysis

        a. Current success rate: 12.7% baseline subscription rate

## Next Steps and Recommendations
    
      1. Model

        a. Deploy the Tuned Logistic Regression model for campaign targeting
        b. Set up A/B testing framework
        
      2. Data Quality Improvements

        a. Address the unknown data issue
        b. Create systematic follow-up processes for incomplete client profiles
        
      3. Campaign Optimization

        a. Target the right audience
