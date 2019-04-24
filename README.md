----

### Machine Learning

This course provides an introduction to machine learning. Machine learning explores the study and construction of algorithms that can learn from and make predictions on data. Such algorithms operate by building a model from example inputs in order to make data-driven predictions or decisions, rather than following strictly static program instructions.

Topic categories include supervised, unsupervised, and reinforcement learning. Students will learn how to apply machine learning methods to solve problems in computer vision, natural language processing, classification, and prediction. Fundamental and current state-of-the-art methods including boosting and deep learning will be covered. Students will reinforce their learning of machine learning algorithms with hands-on tutorial oriented laboratory exercises using Jupyter Notebooks.

Prerequisites: MA-262 Probability and Statistics; programming maturity, and the ability to program in Python.  

Helpful: CS3851 Algorithms, MA-383 Linear Algebra, Data Science.  

ABET: Math/Science, Engineering Topics.

2-2-3 (class hours/week, laboratory hours/week, credits)

Lectures are augmented with hands-on tutorials using Jupyter Notebooks. Laboratory assignments will be completed using Python and related data science packages: NumPy, Pandas, ScipPy, StatsModels, Scikit-learn, Matplotlib, TensorFlow, Keras, PyTorch.

Outcomes:   
- Understand the basic process of machine learning.    
- Understand the concepts of learning theory, i.e., what is learnable, bias, variance, overfitting.  
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.  
- The ability to analyze a data set including the ability to understand which data attributes (dimensions) affect the outcome.  
- Understand the application of learned models to problems in classification, prediction, clustering, computer vision, and NLP.  
- Understand deep learning concepts and architectures including representation learning Multi-layer Perceptrons, Convolutional Neural Networks, Recurrent Neural Networks, and Attention Mechanisms.    
- The ability to assess the quality of predictions and inferences.  
- The ability to apply methods to real world data sets.  

References:  

*[Hands-On Machine Learning with Scikit-Learn and TensorFlow
Concepts, Tools, and Techniques to Build Intelligent Systems (MLSLT), Aurélien Géron. O'Reilly Media, 2017](http://shop.oreilly.com/product/0636920052289.do)

[Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow, 2nd Edition, by Aurélien Géron, Publisher: O'Reilly Media, Inc. Release Date: June 2019
ISBN: 9781492032649](https://www.safaribooksonline.com/library/view/hands-on-machine-learning/9781492032632/)

*[Deep Learning with Python (DLP), François Chollet. Manning, 2017.](https://www.manning.com/books/deep-learning-with-python)

[Deep Learning (DL), Ian Goodfellow, Yoshua Bengio, and Aaron Courville. MIT Press, 2016.](https://www.deeplearningbook.org/)

[An Introduction to Statistical Learning: with Applications in R (ISLR), Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani. 2015 Edition, Springer.](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Seventh%20Printing.pdf)

[Python Data Science Handbook (PDSH), Jake VanderPlas, O'Reilly.](https://jakevdp.github.io/PythonDataScienceHandbook/)

Mining of Massive Datasets (MMDS). Anand Rajaraman and Jeffrey David Ullman. http://www.mmds.org/

---

### Week 1: Intro to Machine Learning

#### Lecture:    
1. [Syllabus](syllabus.pdf)

1. [Introduction to Machine Learning](slides/IntroMachineLearning.pdf)  
- Demonstrations   
- Reading: MLSLT Ch. 1  

2. [Introduction to Git and GitHub](slides/00_git_github.pdf)
-  Reference: [git - the simple guide](http://rogerdudler.github.io/git-guide/)   

3. [Machine Learning Foundations](slides/MachineLearningFoundations.pdf)  
- [End to end machine learning](notebooks/02_end_to_end_machine_learning_project.ipynb)  
- [Image Classification Using Deep Learning](https://github.com/jayurbain/deep-learning-foundations/blob/master/image-classification/dlnd_image_classification.ipynb)  
- [Back Pain](https://github.com/jayurbain/BackPain/blob/master/Back%20Pain%20Data%20Analysis.ipynb)     
- [Vehicle Detection](https://github.com/jayurbain/CarND-Vehicle-Detection)    
- Reading: MLSLT Ch. 2   

#### Lab Notebooks:
- [Using Jupyter Notebooks](notebooks/lab_0_python/lab_0_jupyter.ipynb)    
- [Python Programming for Data Science](notebooks/lab_0_python/lab_0_python.ipynb) *Submission required*
- [Python Numpy](notebooks/4&#32;-&#32;Python&#32;Numpy.ipynb) *Submission required*    

#### Optional tutorial notebooks:   
- [Python Objects, Map, Lambda, and List Comprehensions](<notebooks/3&#32;-&#32;Python&#32;Objects&#32;Map&#32;Lambda&#32;List&#32;Comprehensions.ipynb>) 
- [Dates and Time](notebooks/2&#32;-&#32;Dates&#32;and&#32;TIme.ipynb)  
- [Python Numpy Aggregates](notebooks/5&#32;-&#32;Python&#32;Numpy&#32;Aggregates.ipynb)
- [Pandas Data Manipulation](notebooks/6&#32;-&#32;Pandas&#32;Data&#32;Manipulation.ipynb)   
- [Python Reading and Writing CSV files](notebooks/7&#32;-&#32;Python&#32;Reading&#32;and&#32;Writing&#32;CSV&#32;files.ipynb)  
- [Data Visualization](notebooks/8&#32;-&#32;Data&#32;Visualization.ipynb)  
- [Python Programming Style](notebooks/lab_0_python/python_programming_style.ipynb) 

Outcomes addressed in week 1:   
- Understand the basic process of machine learning:    
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.  

---

#### Week 2: Linear Regression, Multivariate Regression  

#### Lecture:

1. [Linear Regression 1](slides/08_linear_regression.pdf)
- Reading: PDSH Ch. 5 p. 331-375, 390-399  
- Reading: ISLR Ch. 1, 2  

2. [Linear Regression Notebook](notebooks/08_linear_regression.ipynb) *Use for second lecture*   
- [Normal Equation Derivation](http://jayurbain.com/msoe/cs498-machinelearning/Normal%20Equation%20derivation%20for%20linear%20regression.pdf)    
- Reading: ISLR Ch. 3  
- Reading: PDSH Ch. 5 p. 359-375   

3. [Generalized Linear Models Notebook](notebooks/Generalized%20Linear%20Models%20and%20Regularization.ipynb) *Optional* 

#### Lab Notebooks:  

- [Introduction to Machine Learning with Scikit Learn](notebooks/Lab3_LinearRegression/Introduction&#32;to&#32;Machine&#32;Learning&#32;with&#32;SciKit&#32;Learn.ipynb)    
- [Supervised Learning Linear Regression](notebooks/Lab3_LinearRegression/Supervised&#32;Learning&#32;-&#32;&#32;Linear&#32;Regression.ipynb) *Submission required*  
- [Bike Demand Linear Regression](notebooks/Lab3_LinearRegression/bike-sharing-demand-regression.ipynb) *Optional extra credit submission*  

Outcomes addressed in week 4:   
- The ability to analyze a data set including the ability to understand which data attributes (dimensions) affect the outcome.  
- The ability to perform basic data analysis and statistical inference.  
- The ability to perform supervised learning of prediction models.
- The ability to perform data visualization and report generation.   
- The ability to apply methods to real world data sets.

---

### Week 3: Introduction to Classification, KNN, Model Evaluation and Metrics. Logistic Regression

#### Lecture:  
1. [Linear Model Selection and Regularization](slides/linear_model_selection_and_regularization.pdf)   
- Reading: ISLR Ch. 6    

2. [Introduction to Machine Learning with KNN](slides/06_machine_learning_knn.pdf)  
- Reading: ISLR Ch. 4.6.5  

3. [Logistic Regression Classification](slides/09_logistic_regression_classification.pdf)  
- Reading: ISLR Ch. 4  

#### Lab Notebooks:   
- [Gradient Descent](notebooks/gradient_descent_assignment.ipynb)   *Submission required*   
- [Linear Regression - Recursive Feature Elimination - Bike sharing data set](notebooks/Lab3_LinearRegression/bike-sharing-demand-regression-rfe.ipynb)   *Submission required*

Outcomes addressed in week 4:     
- The ability to assess the quality of predictions and inferences.  
- The ability to apply methods to real world data sets.  
- The ability to perform supervised learning of prediction models.  

---

### Week 4: Logistic Regression, Model Selection and Regularization, ROC 

#### Lecture:   

1. [Logistic Regression Classification](slides/09_logistic_regression_classification.pdf)  
- Reading: ISLR Ch. 4  

2. [Model Evaluation and Metrics, ROC](slides/07_model_evaluation_and_metrics.pdf)   
- [Scikit-learn ROC Curve notebook](notebooks/plot_roc.ipynb)  
- Reading: PDSH Ch. 5 p. 331-375, 390-399   
- Reading: ISLR Ch. 5 

3. [Regularization and overfitting](slides/Regularization_and_overfitting.pdf) 

#### Lab Notebooks:
- [Supervised Learning - Logistic Regression](notebooks/Lab5_Logistic_Regression/Supervised&#32;Learning&#32;-&#32;Logistic&#32;Regression.ipynb)   *Submission required*   
- [Multinomial Image Classification](notebooks/multinomial_classification.ipynb) *submission required*     
- If you're having trouble reading MNIST from mldata use the following notebook to load the data:  
[Write Read MNIST](notebooks/write_read_MNIST.ipynb)   
- [mnist_data.csv](https://drive.google.com/open?id=1p-K8JpCEiATE7VrBNsfruYtn4ivorceW)  
- [mnist_target.csv](https://drive.google.com/open?id=1TnARZEzS0CPhco_MxpkVbf31zYqkuFbL)  

Outcomes:  
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.  
- The ability to analyze a data set including the ability to understand which data attributes (dimensions) affect the outcome.  
- Understand the application of learned models to problems in classification, prediction, clustering, computer vision, and NLP.      
- The ability to assess the quality of predictions and inferences.  
- The ability to apply methods to real world data sets.  

 
#### Week 5: Decision Trees, Bagging, Random Forests

#### Lecture:   

1. [Decision Trees](slides/08_decision_trees.pdf)   
- Reading: PDSH Ch. 5 p. 421-432  
- Reading: ISLR Ch. 8.1    
- [Information Gain Calculation Spreadsheet](http://jayurbain.com/msoe/cs4881/infogain.xls)

2. [Bagging, Random Forests, Boosting](slides/Bagging_RF_Boosting.pdf)  
- Reading: PDSH Ch. 5 p. 421-432  
- Reading: ISLR Ch. 8.2   

#### Lab Notebooks: 
- [Decision Trees](notebooks/Lab7_DecisionTrees/Decision&#32;Trees.ipynb) *submission required*

  
Outcomes:  
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.  
- The ability to analyze a data set including the ability to understand which data attributes (dimensions) affect the outcome.  
- Understand the application of learned models to problems in classification, prediction, clustering, computer vision, and NLP.      
- The ability to assess the quality of predictions and inferences.  
- The ability to apply methods to real world data sets. 
---

#### Week 6: Boosting, XGBoost, Midterm

#### Lecture:  

1. [Gradient Boosting, XGBoost](slides/gradient_boosting.pdf)  

2. [Midterm Exam](handouts/Midterm-Review.pdf)

#### Lab Notebooks:  
- [Random Forests](notebooks/Random-Forests.ipynb) *recommended for study, submission not required*   
- [Random Forests and Gradient Boosting](notebooks/XGBoost.ipynb) *recommended for study, submission not required*  
- [Ensembling](notebooks/16_ensembling.ipynb)  *optional, not required*   

Outcomes:    

Outcomes:  
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.  
- The ability to analyze a data set including the ability to understand which data attributes (dimensions) affect the outcome.  
- Understand the application of learned models to problems in classification, prediction, clustering, computer vision, and NLP.      
- The ability to assess the quality of predictions and inferences.  
- The ability to apply methods to real world data sets. 

---

#### Week 7: Introduction to Deep Learning and Backpropagation  

#### Lecture:

1. [Deep Learning Introduction 1](slides/Deep&#32;Learning&#32;Introduction.pdf)  
Reference for earlier in class:   
- [Gradient Descent](slides/LogisticRegressionML_Jay.pdf)   
- [Gradient Descent notebook](notebooks/GradientDescent.ipynb)   

2. [Deep Learning Introduction 2](slides/Deep&#32;Learning&#32;Introduction.pdf)

3. [Backpropagation](slides/backpropagation.pdf)   

#### Lab Notebooks:    
- [NeuralNetworkIntro](notebooks/NeuralNetworkIntro.ipynb)   *submission required*    
- Additional Google Colab notebooks:    
Install TensorFlow:   
conda install -c conda-forge tensorflow   

&nbsp;&nbsp;Complete the following TensorFlow "Learn and use ML" tutorials. Submit 
&nbsp;&nbsp;screen shot demonstrating complete of the tutorial along with feedback
to Blackboard.   

&nbsp;&nbsp;Get Started with TensorFlow   
- https://www.tensorflow.org/tutorials/   

&nbsp;&nbsp;Train your first neural network: basic classification   
- https://www.tensorflow.org/tutorials/keras/basic_classification   

&nbsp;&nbsp;Explore overfitting and underfitting   
- https://www.tensorflow.org/tutorials/keras/overfit_and_underfit   

Optional: 
- [MNIST with CNN](notebooks/deep_learning_intro/mnist_cnn.ipynb) *Optional*      
- Work on the other "Learn and use ML" tutorials. *Optional*          
- [Introduction to TensorFlow](notebooks/deep_learning_intro/Tensorflow-task.ipynb) *Optional*   
- [Neural Network Fundamentals](notebooks/deep_learning_intro/my1stNN.ipynb) *Optional*       

Reading:    
- DLP Chs. 1-4    

Outcomes addressed in week 8:
- Understand the concepts of learning theory, i.e., what is learnable, bias, variance, overfitting.  
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.   
- Understand the application of learned models to problems in classification, prediction, clustering, computer vision, and NLP.  
- Understand deep learning concepts and architectures including representation learning Multi-layer Perceptrons, Convolutional Neural Networks, Recurrent Neural Networks, and Attention Mechanisms.    

#### Week 8: Deep Learning for Computer Vision

#### Lecture:

1. [Convolutional Neural Networks 1](slides/cnn_1.pdf)  

2. [Convolutional Neural Networks 2](slides/cnn_1.pdf)  

Reading:  
- DLP Ch. 5  

#### Lab Notebooks: 

Setting up your environment:   
- First, do a `git pull` on the course repository.    

Note: You may run the lab notebooks in Google Collab. You will need a Google account and will need to store datasets in your own Google Drive folder. 
  https://colab.research.google.com/notebooks/welcome.ipynb    

Use the follow procedure when opening one of our course notebooks in Collab:   
- Select: NEW PYTHON 3 NOTEBOOK   
- Once the notebook opens, select EDIT, NOTEBOOK SETTINGS, and select GPU. You can also select Python 3 here as well.   
- Select FILE, OPEN, UPLOAD and upload your notebook.   
- For the notebooks that use the cat and dog images, you will need to upload those files to a folder on your Google Drive.    

If you want to run tensorflow and keras locally, use the following installation procedure:    
- [Tensorflow Keras Jupyter Install Cheat Sheet](tensorflow_keras_jupyter_install_cheat_sheet.txt)    

Notebooks:   
- [Keras Neural Network Intro](notebooks/deep_learning_intro/a-first-look-at-a-neural-network.ipynb) *Review only* 
- [Convnets with Small Datasets](notebooks/dlp/convnets-with-small-datasets.ipynb) *Submission required*      
- [Image Classification](notebooks/computer_vision/cnn_cifar10.ipynb) *Extra Credit*  

Optional material:
- [Deep Learning for Computer Vision](slides/dli/Lecture-3-1-convnets-history-urbain.pdf)  
- [Convnets](slides/dli/Lecture-3-2-convnets-intro-urbain.pdf)

Outcomes addressed in week 9:
- Understand the concepts of learning theory, i.e., what is learnable, bias, variance, overfitting.    
- Understand the application of learned models to problems in classification, prediction, clustering, computer vision, and NLP.  
- Understand deep learning concepts and architectures including representation learning Multi-layer Perceptrons, Convolutional Neural Networks, Recurrent Neural Networks, and Attention Mechanisms.    

---

#### Week 9: Deep Learning for NLP

#### Lecture:

1. [NLP Classification](slides/nlp/2&#32;NLP%20Text&#32;Classification.pdf)  

2. *Optional* [Convnets for Structured Prediction](slides/dli/Lecture-3-3-convnets-struc-pred-nlp-urbain.pdf)  

#### Lab Notebooks:     
- [NLP Classification](notebooks/nlp/Text&#32;Classification/SentimentClassification.ipynb)  *Submission required*      
- [NLP Translation ](notebooks/nlp/Text&#32;Translation/TextTranslation.ipynb) *Extra Credit*     

Outcomes addressed in week 9:   
- Understand the concepts of learning theory, i.e., what is learnable, bias, variance, overfitting.  
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.   
- Understand the application of learned models to problems in classification, prediction, clustering, computer vision, and NLP.  
- Understand deep learning concepts and architectures including representation learning Multi-layer Perceptrons, Convolutional Neural Networks, Recurrent Neural Networks, and Attention Mechanisms.    

---

#### Week 10:  Generative Deep Learning

#### Lecture:
1. [NLP Translation](slides/nlp/3&#32;NLP&#32;Text&#32;Translations.pdf)    

2. [Deep Learning Trends NLP ](slides/DeepLearningTrendsNLP2019.pdf)[DeepLearningTrendsNLP2019]

3. [Final Review Study Guide](handouts/Final-Review.pdf)   

#### Lab Notebooks:  
Complete assignments   

Outcomes addressed in week 10:
- Understand the concepts of learning theory, i.e., what is learnable, bias, variance, overfitting.  
- Understand the concepts and application of supervised, unsupervised, semi-supervised, and reinforcement learning.   
- Understand the application of learned models to problems in classification, prediction, clustering, computer vision, and NLP.  
- Understand deep learning concepts including representation learning.    

---

Final Exam: Monday, 8-10AM, S243.


Thomas More Catholic Church, 215 Thomas More Drive, Elgin

 where she was a parishioner. Visitation will be held on Friday morning at the church from 9:30 AM until the time of mass. In lieu of flowers, the family requests donations be made to Ronald McDonald House.