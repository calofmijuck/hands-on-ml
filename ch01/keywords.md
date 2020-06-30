### Keywords

* 'Machine Learning'

Building a system that can learn from data.

* Labeled training set

Each sample contains an answer(label)

* Supervised learning methods

  + Regression
  + Classification

* Unsupervised learning methods

  + Clustering
  + Visualization
  + Dimensionality reduction
  + Association rule learning

* Online learning system

  + Can learn incrementally, adaptive to fast-changing data/system

* Out of core learning

  + Training with large sized data. Split the dataset into mini-batches and use online learning method

* Model parameter

  + The parameters that the model has to learn from the dataset. This parameter will be used to predict from inputs.

* Hyperparameter

  + The parameter of the algorithm itself. Ex) Regularization term, size of mini-batch

* Model based learning algorithm

  + Find optimal values of the model parameter that will generalize well

* Test set

  + Used to test the model and quantify the generalization error

* Validation set

  + Used to compare the models and tune hyperparameters

* Hyperparameter tuning with test set  

  + This is prone to overfitting, generalization error will be small

* Cross validation
  
  + Lets you compare different models without having to separate the validation set from the test data, which lets you use your dataset more efficiently
