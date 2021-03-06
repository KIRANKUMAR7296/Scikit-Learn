# Logistic Regression

### Classification

Problems with Discrete and Finite Output called **Classes** or **Categories**

### Types of Classification

1. Binary | Binomial | Dichotomous (Exactly Two | 0 or 1 | True or False | Positive or Negative)
2. Multiclass | Multinomial (Three or more classes of Outputs to Choose from)

### When do you Need Classification?
1. Spam Emails
2. Medical Applications 
3. **Biological** Classification
4. Credit Scoring

### Sigmoid Function (S Shaped Curve)
**Sigmoid** Function has values very close to either **0** or **1**

![Sigmoid](Image/SigmoidFunction.png) 

### Natural Logarithm Function 
**Logarithm** Function has values between 0 and 1

![Logarithm](Image/LogFunction.png) 

### Classification Performance

![Confusion Matrix](Image/ConfusionMatrix.jpg)

1. **True Positive** (**TP**) : Correctly Predicted Positives 
2. **True Negative** (**TN**) : Correctly Predicted Negatives
3. **False Positive** (**FP**) : Incorrectly Predicted Positive (**Type I** Error | **alpha** | Accept **NULL** Hypothesis)
4. **False Negative** (**FN**) : Incorrectly Predicted Negative (**Type II** Error | **beta** | Do not Accept **NULL** Hypothesis)

![Confusion Matrix](Image/CM.png)

Positive Predictive Value : TP / TP + FP

Negative Predictive Value : TN / TN + FN

**Recall** | True Positive Rate (**TPR**) | **Sensitivity** : TP / TP + FN (**Prediction**)

**Precision** | True Negative Rate (**TNR**) : TP / TP + FP (**Actual**)

**Specificity** : TN / TN + FP 

**Accuracy** : TP + TN / TP + TN + FP + FN (**Total**)

### Single Variate Logistic Regression
- Only One Independent Feature

### Multi Variate Logistic Regression
- More than one Independent Feature
