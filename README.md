# neural-network-challenge-2

Creating a neural network that HR can use to predict whether employees are likely to leave the company. Additionally, HR believes that some employees may be better suited to other departments, so you are also asked to predict the department that best fits each employee. These two columns should be predicted using a branched neural network.

# Summary

In the provided space below, briefly answer the following questions.

1. Is accuracy the best metric to use on this data? Why or why not?

2. What activation functions did you choose for your output layers, and why?

3. Can you name a few ways that this model might be improved?


MY ANSWERS 

1. Accuracy might not be the best metric if the classes are imbalanced, if there are significantly more employees who don't leave the company than those who do. In such cases, other metrics like precision, recall, and F1-score might be more informative.
2. **Department:** 'softmax' is used because it's a multi-class classification problem (predicting one of several departments).

    **Attrition:** 'sigmoid' is used because it's a binary classification problem (predicting whether an employee will leave or stay).

3. **Feature engineering:** Create new features or transform existing ones to improve model performance.

    **Regularization:** Add techniques like dropout or L1/L2 regularization to prevent overfitting.

    **Different model architectures:** Explore other model types like Random Forest or Gradient Boosting.
  
    **Address class imbalance:** If the data is imbalanced, consider techniques like oversampling, undersampling, or using weighted loss functio
