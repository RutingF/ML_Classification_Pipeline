# ML_Classification_Pipeline
Exploring Support Vector Machines (SVM) and Decision Trees for classification projects. 

## DecisionTree 
In the classify_poisonous_mushroom jupyter notebook, I explored using a **Decision Tree Classifier** to determine feature importance in a dataset. 

**Evaluation**
From the UCI Mushroom dataset, we saw the accuracy of Decision Tree classifier is 100% on both training and test data, which led to concerns of overfitting. 

![Decision Tree Visualization](doc/decisiontree.png)

To avoid overfitting and achieve generalization, we can consider below approaches: 

- Control the **maximum depth** of the tree
- Average multiple trees to improve generalization, such as **Random Forests** or **Gradient Boosted Trees** 
