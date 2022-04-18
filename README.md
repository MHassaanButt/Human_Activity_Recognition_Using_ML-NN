# Human Activity Recognition using smartphone Data

## Required Python Libraries

Use the requirements.txt file to install all the required dependencies to run the code.

```pip install -r requirements.txt```

## Dataset Descrption
Human activity recognition using smartphone data using dataset from the UCI Machine Learning Repository. The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, They captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

## Algorithm Descrption
For project demontration we used Logsitic Regression, K Nearest Neighbors, Random Forest, Support Vector Machine and Neural Networks for human activity recognition.

**Logistic regression:** is a process of modeling the probability of a discrete outcome given an input variable. The most common logistic regression models a binary outcome; something that can take two values such as true/false, yes/no, and so on.

The **k-nearest neighbors (KNN)** algorithm is a simple, supervised machine learning algorithm that can be used to solve both classification and regression problems. It's easy to implement and understand, but has a major drawback of becoming significantly slows as the size of that data in use grows.

**Random forest** is a Supervised Machine Learning Algorithm that is used widely in Classification and Regression problems. It builds decision trees on different samples and takes their majority vote for classification and average in case of regression.

**SVM or Support Vector Machine** is a linear model for classification and regression problems. It can solve linear and non-linear problems and work well for many practical problems. The idea of SVM is simple: The algorithm creates a line or a hyperplane which separates the data into classes.

**Neural networks**, also known as artificial neural networks (ANNs) or simulated neural networks (SNNs), are a subset of machine learning and are at the heart of deep learning algorithms. Their name and structure are inspired by the human brain, mimicking the way that biological neurons signal to one another.

## Comparison Table

| Classifiers | Testing Accuracy |
| --- | --- |
| `Logestic Regression` | **95.65659993** |
| `K-nearest neighbors (KNN)` | **90.02375297** |
| `Random forest` | **92.36511707** |
| `SVM` | **96.16559213** |
| `Neural Networks` | **96.43705487** |

## Conclusion
In this particular project, we explored the activity recognition dataset. I applied numerous machine learning algorithms & Neural Networks and found out that Neural Netowrks, Support Vector Machine (SVM) and Logestic Regression give similar kind of accuracy. Although Neural Netowrk performed the best in classifying different activities with accuracy of almost 96% which is relaitvely higher than others classfiers.
