# FINM-33160-W23

We are going to construct a large data set of fundamental factors of stocks. Using various ML models:  Decision Trees, Random Forests, Gradient Boosting etc. we use this data set to design an  algorithmic trading strategy. Thus the course will focus more on practical applications than on the mathematics behind the algorithms, though we will explain some of the ideas behind them.

 

The course will be very computational intensive and we will use a large number of Python packages for training and back testing the models. We will learn to perform an extensive statistical analysis of the results of back tests.

 

In the first lecture we will introduce decision tree classifiers, how they are trained and used to make predictions. 

Also in the first lecture we will set up our data set of fundamental stock data and use them to compute a number of financial ratios that are used in valuing stocks. We make heavy use of the Pandas Python package and we will go over a number of Pandas methods and commands. We also introduce the strategy we will spend most of the course developing and testing.

 

In lecture 2 we will apply a decision tree classifier to the data and train a model it give buy or sell recommendations. We will discuss some of the problems with Machine Learning models, most importantly the concepts of bias and variance and overfitting. We spend some time discussing feature importance and selection to find a set of features that optimize the profit of the strategy. We write a simple program to do a rough back testing of the strategy.

 

In lecture 3 we begin our study of randomizing and ensembles of classifiers to increase the predictive power of the single classifier. The idea of ensemble classifiers is to construct a number of independent classifiers, each of which may not be very accurate but in the average works well. In this lecture we discuss bootstrapping and 'bagging' of trees. We explain the various parameters of the ensemble and how the various combinations affect the accuracy of the ensemble. We then fit a bagging tree classifier. Again the question of feature selection is central and we will discuss a couple of ways to find good feature sets. 

 

Lecture 4 turns to random forests which is a further randomization of bagging trees. This is an important classifier which is widely used in practice. We will do a deep dive into random forests and spend most of this lecture writing our own code to construct a random forest classifier. Even though there is a perfectly good classifier in the sklearn library (which in practice is what we will use) writing our own code is both good practice in Python programming and understanding how the classifier works.

 

In lecture 5 we apply the random forest classifier to our strategy and again look at all the parameters of a random forest to see how various combinations affect performance. We apply our feature selection techniques to find an optimal set of parameters and run the back test of the strategy and compare it to the performance of the benchmark index.

 

Lecture 6 is concerned with boosting algorithms, AdaBoost and Gradient Boosting. We go over the underlying theory behind boosting and discuss loss functions and algorithms to minimize loss function. Both of the boosting algorithms are based on trees but in case of gradient boosting we need to introduce Regression Trees which instead of categorical values outputs continuous values. The training of regression trees uses a different criterion for optimizing splits but in essence is very similar to tree classifiers.

 

The rest of the course will deal with deep learning i.e. Neural Networks. We will look at various architectures such as Convolutional Networks and Recurring Neural Nets. The applications here will be mostly to image recognition and manipulation

 

The course will have 4  home work assignments, a midterm in-class exam and a final. The grading will be based on 35% home work, 20% mid term, 35% final. Every week a small discussion topic will be posted and everyone is required to participate on the discussion board. 10% of the grade will be based on participation on the discussion board.

Some weeks there will be a small (15 min) multiple choice quiz which will also count towards the final grade
