# ML_Classification_Pipeline
Exploring Support Vector Machines (SVM) and Decision Trees for classification projects. 

## DecisionTree 
In the classify_poisonous_mushroom jupyter notebook, I explored using a **Decision Tree Classifier** to determine feature importance in a dataset. 
![Decision Tree Visualization](doc/decisiontree.png)

**Evaluation**
For the classification model, I evaluated performance using metrics such as precision, recall, F1 score, and accuracy while making sure we have equal class distribution. 

Using the UCI Mushroom dataset, the Decision Tree classifier achieved 100% accuracy on both the training and test data, which led to concerns of overfitting. 

![Decision Tree Evaluation](doc/evaluation_decisiontree.png)

To avoid overfitting and achieve generalization, we can consider below approaches: 

- Control the **maximum depth** of the tree
- Average multiple trees to improve generalization, such as **Random Forests** or **Gradient Boosted Trees** 
