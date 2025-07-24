# Supervised Learning Algorithms  
## 1. [Linear Regression](./linear_regrcat_boostession.ipynb)
**[Linear regression](./linear_regression.ipynb)** is a technique used to predict continuous numerical values by establishing the best-fitting straight line that represents the relationship between an input (independent variable) and an output (dependent variable). 
* It works by minimizing the difference between the actual and predicted values through a method known as least squares, which aims to find the most accurate fit for the data.
* Typical examples include predicting a person's weight based on their height or estimating house prices based on their size.

## 2. [Logistic Regression](logistic_regression.ipynb)
**[Logistic regression](logistic_regression.ipynb)** is a classification algorithm that predicts the probability of a data point belonging to a particular class, typically binary (e.g., spam vs. not spam). 
* It models the relationship between input features and class probabilities using the logistic (sigmoid) function, which produces an S-shaped curve.
* This algorithm is widely used for both binary and multi-class classification tasks.
* Instead of outputting direct class labels, it produces probabilities that are then used to assign inputs to categories.
* Examples include predicting whether a customer will make an online purchase (yes/no) or diagnosing whether a patient has a specific disease (sick/not sick).

## 3. [Decision Tree](decision_tree.ipynb)
A **[decision tree](decision_tree.ipynb)** organizes data into branches by splitting it according to feature values, forming a tree-like structure. 
* Each internal node represents a decision based on a feature, while the leaf nodes deliver the final output.
* This process continues until a prediction is reached at a leaf node and can be applied to both classification and regression problems.
* Would you like me to make it even shorter for quick notes or expand it for a more descriptive explanation (like for a study guide)?


## 4. [Support Vector Machines](./support_vector_machines.ipynb) (SVM)
**[Support Vector Machines](./support_vector_machines.ipynb)** (SVMs) determine the optimal boundary, known as a hyperplane, that separates data points into distinct classes.
* They rely on support vectors—the critical data points nearest to the boundary—to define this hyperplane.
* By using kernel functions, SVMs can handle both linear and non-linear classification problems.
* Their key strength lies in maximizing the margin between classes, making them effective for high-dimensional and complex datasets.
 

## 5. [k-Nearest Neighbors](./k_nearest_neighbors.ipynb) (k-NN)
The [k-Nearest Neighbors](./k_nearest_neighbors.ipynb) (KNN) algorithm predicts outcomes for new data points by comparing their similarity to nearby examples in the training set.
It measures distance using metrics like Euclidean, Manhattan, or Minkowski.
The algorithm selects the k closest neighbors based on these distances:
* Classification: assigns the class most frequently occurring among the neighbors.
* Regression: predicts the value as the average of the neighbors’ values.



## 6. [Naive Bayes](./naive_bayes.ipynb)
[Naive Bayes](./naive_bayes.ipynb) is a probabilistic algorithm based on Bayes’ theorem, assuming all features are independent (hence the term “naive”).  
* It calculates the probability of each class for a given data point and assigns the class with the highest probability.
* Although the independence assumption is rarely true in real-world data, Naive Bayes performs well, especially with high-dimensional datasets.
* It is widely used in text classification tasks such as spam detection.


## 7. [Random Forest](./random_feature.ipynb)
[Random Forest](./random_feature.ipynb) is an ensemble learning method that combines multiple decision trees to improve prediction accuracy.
* It introduces diversity among trees through random sampling of data and random feature selection at each split.
* For predictions, it uses majority voting in classification tasks and averaging in regression tasks.
* This approach reduces overfitting compared to a single decision tree and effectively handles large, high-dimensional datasets.



## 8. Gradient Boosting (e.g., [XGBoost](./xg_boost.ipynb), [LightGBM](./light_gbm.ipynb), [CatBoost](./cat_boost.ipynb))
Gradient Boosting builds models sequentially, where each new model focuses on correcting the errors of the previous ones.
It combines multiple weak learners (often decision trees) to form a strong predictive model and works well for both regression and classification tasks.  
Popular Variants:
* [XGBoost](./xg_boost.ipynb) (Extreme Gradient Boosting): Adds regularization to reduce overfitting and is optimized for speed, making it efficient for large datasets.
* [LightGBM](./light_gbm.ipynb) (Light Gradient Boosting Machine): Uses a histogram-based algorithm for faster training and supports categorical features natively.
* [CatBoost](./cat_boost.ipynb): Specially designed for categorical data, using built-in encoding methods and symmetric trees for faster training and better generalization.




## 9. [Neural Networks](./neural_network.ipynb) ( Including Multilayer Perceptron)
[Neural Networks](./neural_network.ipynb), including Multilayer Perceptrons (MLPs), are supervised learning algorithms that rely on labeled data to learn the mapping between inputs and outputs.
They adjust internal weights using the backpropagation algorithm to minimize prediction errors during training.

Multilayer Perceptron (MLP):
* A type of neural network with multiple layers of interconnected nodes.
* It is widely used for both classification (e.g., image recognition, spam detection) and regression tasks (e.g., predicting stock or house prices).

