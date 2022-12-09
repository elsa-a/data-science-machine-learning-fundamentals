# Predicting Data with Machine Learning
Selection of **Data Science projects that use classical ML algorithms for prediction or data analysis**. Projects from the modules AI and Machine Learning (CS 6002) and Introduction to Data Engineering and Machine Learning (CE4051) taken in my MSc.

## Prediction with Advanced Models

### Separating data whith highly complex boundaries: Non-linear classification.

In Advance Machine Learning, Algorithms are able to weigh the features of the data fed to that Algorithm in order to make the most accurate prediction **without explicity declaring those features to the model**, which allows prediction of data in complex scenarios, for example non-linearly separable data in classification problems.

Below, Kernel SVMs and Neural Nets implementations for complex **non-linear data classification**. Projects involve tuning hyperparameters and Bayesian optimisation.

[Kernel SVMs and Neural Network implementation](https://github.com/elsa-a/data-science-machine-learning-fundamentals/blob/main/Etivity3_CE6002.ipynb
).

[Kernel SVMs for non-linear multi-class classification](https://github.com/elsa-a/data-science-machine-learning-fundamentals/blob/main/Etivity4_Option2_Part2_3_21272808.ipynb).

## Unsupervised Learning 
### Dimensionality Reduction for efficient predictions
When a dataset contains too many variables, it might not be clear which ones to choose for the model, and it is typically too costly to use all of them. 
PCA analyses correlations between variables and find new vectors in the feature space that **best describe the data using less variables**, for example reducing natural redundancies in the data. This allows for better predictions as it uses less dimensions while still mantain the latent relations of the data.

[Reduction of a high-dimensional dataset for improved performance](https://github.com/elsa-a/data-science-machine-learning-fundamentals/blob/main/Etivity5_DimensionalityReduction_21272808.ipynb).


## Prediction with simpler Machine Learning models
Regular ML algorithms are adecuate for prediction of simple linear problems and require the features to be declared explicitly.

### Salary prediction and flower species classification (Multi-class classifier) with Linear SVMs

[Flower Classification with Linear SVM](https://github.com/elsa-a/data-science-machine-learning-fundamentals/blob/main/Etivity4_Option2_Part1_21272808.ipynb)

[Salary Prediction with Linear SVM for Regression](https://github.com/elsa-a/data-science-machine-learning-fundamentals/blob/main/Etivity5_FeatureSelection_21272808.ipynb)


### Gender prediction through NB Classification (Binary classifier)

Training of a Classifier for prediction of the gender of a person using the **Naive-Bayes classification** algorithm.

[NB classifier for gender prediction here](https://github.com/elsa-a/data-science-machine-learning-fundamentals/blob/main/Etivity2_NaiveBayes_21272808.ipynb).

### Flower species prediction through the perceptron algorithm (Binary classifier) 
Demonstration of how the **perceptron algorithm** can be trained to learn the weights for input signals in order to draw linear decision boundary that allows us to discriminate between the two linearly separable classes +1 and -1. 

Below:
* An implementation of **Frank Rosenblatt's Perceptron**, the first algorithmically described neural network based on the idea of the **perceptron learning rule** which later served as the basis for modern multilayer neural networks and the whole field of Deep Learning.

[Frank Rosenblatt's Perceptron implementation from scratch](https://github.com/elsa-a/data-science-machine-learning-fundamentals/blob/main/Etivity3_Perceptron_21272808.ipynb).

* Application of **sklearn's implementation of the perceptron algorithm to predict flower species using the Iris Dataset**

[sklearns perceptron for flower species prediction](https://github.com/elsa-a/data-science-machine-learning-fundamentals/blob/main/Etivity3_ScikitLearn_21272808.ipynb).

