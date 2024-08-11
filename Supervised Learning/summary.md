There are two major types of supervised machine learning problems, called **classification** and **regression**

In classification, the goal is to **predict a class label**, which is a choice from a predefined
list of possibilities. Classification is sometimes separated into binary classification,
which is the special case of distinguishing between exactly two classes, and multiclass
classification, which is classification between more than two classes.

For regression tasks, the goal is to predict a **continuous number**, or a floating-point number in programming terms

If a model is able to make accurate predictions on unseen data, we say it is able to **generalize** from the training set to the test set.

The only measure of whether an algorithm will perform well on new data is the **evaluation** on the test set.

Building a model that is too complex for the amount of information we have, as our novice data scientist did, is called **overfitting**. Overfitting occurs when you fit a model too closely to the particularities of the training set and obtain a model that works well on the training set but is not able to generalize to new data.

Choosing too simple a model is called **underfitting**.

