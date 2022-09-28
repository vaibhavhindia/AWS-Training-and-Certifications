# [The Elements of Data Science](https://www.aws.training/Details/eLearning?id=26598)
In this course, we'll explore the machine learning process from end-to-end. It's important to know how data influences and impacts this process, because your machine learning solution is only as good as the data that drives it.

![The_Elements_of_Data_Science_Certificate](/The_Elements_of_Data_Science/images/The%20Elements%20of%20Data%20Science.PNG)
# CHAPTER - 1

# What is Data Science?
In this section we'll discuss managing, analyzing, and visualizing data. Machine learning models are only useful when you have high-quality data, which can be curated using the data science workflow.

One goal of Data Science is to uncover actionable insights from seemingly disconnected pieces of information .

# Types of Machine Learning
The three types of machine learning: 

### Supervised Learning
Models learn from training data that has been labeled.


### Unsupervised Learning
Models learn from test data that has not been labeled.

### Reinforcement Learning
Models learn by taking actions that can earn rewards.

# Key Issues in ML
This highlights some of the challenges your model will face if you don't have high-quality data.

# Supervised Methods: Linear Regression
linear methods, univariate linear regression, and multivariate linear regression.

# Supervised Learning: Logistic Regression and Linear Separability
logistic regression and linear separability, and explains how they can be applied to a business problem involving a credit card transaction.



# knowledge 1 ( answers )

![Knowledge_Check_1_1](/The_Elements_of_Data_Science/images/Knowledge%20check%201.1.PNG)
![Knowledge_Check_1_2](/The_Elements_of_Data_Science/images/Knowledge%20check%201.2.PNG)
![Knowledge_Check_1_3](/The_Elements_of_Data_Science/images/Knowledge%20check%201.3.PNG)
![Knowledge_Check_1_4](/The_Elements_of_Data_Science/images/Knowledge%20check%201.4.PNG)
![Knowledge_Check_1_5](/The_Elements_of_Data_Science/images/Knowledge%20check%201.5.PNG)
![Knowledge_Check_1_6](/The_Elements_of_Data_Science/images/Knowledge%20check%201.6.PNG)


# CHAPTER - 2 

# Problem Formulation and Exploratory Data Analysis
This section covers best practices for transforming a business problem into a machine learning problem. Additional topics include techniques for data exploration, cleaning, and visualization.

# Problem Formulation
Problem formulation is the starting point for any data science or machine learning project. This section explains that without a thorough, appropriate, and comprehensive definition of the problem, finding a true solution is difficult.

# Data Collection
As we've seen, data collection is an ongoing process throughout any machine learning project. This video explores the details of data collection, and open data on AWS.

# Data Collection: Sampling
This explores two approaches to data collection sampling, and challenges that you should keep in mind when sampling.

# Data Collection: Labeling
The reality is, labeling isn't easy.... but labels are the gold standard from which a machine learning algorithm learns.

Here, we review labeling and discuss the use of Amazon Mechanical Turk as a labeling tool. 

# Exploratory Data Analysis: Domain Knowledge
This section explores what needs to happen with data inside a machine learning workflow, in order to produce a successful business solution. 

## Typical ML workflow
![image](https://user-images.githubusercontent.com/105274023/192725204-1c3b2c63-ea3a-49d0-85f3-61883ef3797e.png)


1 Feature Augmentation


2 Data Augmentation

# Exploratory Data Analysis: Data Schema
 we'll review what to do with data that comes from multiple sources.

## NOTE
"With Amazon SageMaker, we can accelerate our Artificial Intelligence initiatives at scale by building and deploying our algorithms on the platform. We will create novel large-scale machine learning and AI algorithms and deploy them on this platform to solve complex problems that can power prosperity for our customers."

# Exploratory Data Analysis: Data Statistics
This explores what to do once you have your data.

# Exploratory Data Analysis: Correlations
Topics includes linear relationships of a data set, and how to calculate correlation.

# Exploratory Data Analysis: Data Issues
As previously mentioned, it's important to understand the data you're feeding your machine learning model. In this video we'll discuss how to think about messy and/or missing data.


# Knowledge 2 ( answers )
![Knowledge_Check_2_1](/The_Elements_of_Data_Science/images/Knowledge%20check%202.1.PNG)
![Knowledge_Check_2_2](/The_Elements_of_Data_Science/images/Knowledge%20check%202.2.PNG)
![Knowledge_Check_2_3](/The_Elements_of_Data_Science/images/Knowledge%20check%202.3.PNG)

# CHAPTER - 3 

# Data Processing and Feature Engineering
This section of the course defines data processing and feature engineering. We'll talk in more detail about these topics later on in the course but for now, let's take a look at best practices for data processing, and the importance of feature engineering. 

# Data Pre-processing: Encoding Categorical Variables
Algorithms typically expect to see numerical values, however, there are a lot categorical variables that can also be used. This section covers different types of categorical variables that can be encoded for machine learning.

# Data Pre-processing: Encoding Nominals
In this part of the course, we'll discuss how to encode nominal variables.

# Data Pre-processing: Handling Missing Values
While algorithms can handle different types of variables, they cannot handle missing values. Here, you’ll learn how to handle missing values by processing, dropping, or imputing the values.

# Feature Engineering
we’ll briefly introduce feature engineering and why you should base feature engineering on your specific business problem.

# NOTE
Machine learning algorithms not only apply to numerical or categorical variables, but are often applied to images or sound. These data structures are complicated and need filtering in order to fit our business problems.

# Feature Engineering: Filtering and Scaling
This discusses filtering and widely used scaling methods that you can apply to image or sound features.

# Feature Engineering: Transformation
Here, we cover polynomial transformation and radial basis function.

# Feature Engineering: Text-Based Features
you’ll learn about text-based features and the bag-of-words model.

# Knowledge 3 ( answers )

![Knowledge_Check_3_1](/The_Elements_of_Data_Science/images/Knowledge%20check%203.1.PNG)
![Knowledge_Check_3_2](/The_Elements_of_Data_Science/images/Knowledge%20check%203.2.PNG)
![Knowledge_Check_3_3](/The_Elements_of_Data_Science/images/Knowledge%20check%203.3.PNG)
![Knowledge_Check_3_4](/The_Elements_of_Data_Science/images/Knowledge%20check%203.4.PNG)

# CHAPTER - 4 

# Model Training, Tuning, and Debugging
In this section of the course we discuss how you can continuously improve your machine learning models by training, tuning, and debugging them.

# Supervised Learning: Neural Networks
In this exploration of neural networks we feature single-layer neural networks, convolutional neural networks, and recurrent neural networks.

# Supervised Learning: K-Nearest Neighbours
Here, we explore the K-Nearest neighbour methodology and describe how it can be applied to different use cases.

# Supervised Learning: Linear and Non-Linear Support Vector Machines
we’ll discuss linear and non-linear support vector machines and how they are commonly used in industry and in business.

# Supervised Learning: Decision Trees and Random Forests
This covers decision trees and random forests. Deepening your understanding of decision trees and random forests can help you describe entropy and understand the concept of ensembles.

# NOTE
It's rare that machine learning models work the first time. We have to feed in different data and features, applying different algorithms and hyperparameters, to find the best model... We have to train and tune the model.

# Model Training: Validation Set
The training and tuning processes are iterative, and they are not separate from one another. Here, we investigate the training process and see how validation sets help tune models during this phase.
![image](https://user-images.githubusercontent.com/105274023/192729317-34bc2026-247b-464a-8f70-113bbd0672c8.png)

## The Model Training Process:
The execution of an algorithm against a data set, after you've applied some parameters.

## Validation Data Set:
A sample of data used to give an unbiased evaluation of the model, helping you see where to tweak parameters.

## Splitting Up the Data
![image](https://user-images.githubusercontent.com/105274023/192729633-3501f781-7796-4215-9b22-4e5fae676464.png)

### Training data: builds the model 

### Validation data: evaluates the model performance during debugging and tuning 

### Testing data: generalizes the final data set .

# Model Training: Bias Variance Trade-off
Machine learning models depend on input data, output data, and understanding the relationship between the two. Despite training and tuning, it's still difficult to find this mechanism. 

Take a moment to explore how bias and variance affect the relationship between input and output data, before diving into this video on the bias variance tradeoff.

•	Bias: an error from flawed assumptions in the algorithm. High bias can cause an algorithm to miss important relationships between features and target outputs resulting in underfitting.

•	Variance: an error from sensitivity to small variations in the training data. High variance can cause an algorithm to model random noise in the training set, resulting in overfitting.
![image](https://user-images.githubusercontent.com/105274023/192730223-8889956c-a754-4e7e-9ae8-455a5f3324c3.png)

## Solution
•	Try new features
•	Decrease the degree of regularization

![image](https://user-images.githubusercontent.com/105274023/192730398-9ea4b3c3-9b88-4a5f-bf71-3d0b921ccd5e.png)

## Solution
•	Increase training data
•	Decrease the number of features

# Model Debugging: Error Analysis
We know that finding the relationship between input and output data is challenging, and models are prone to error. This section covers how to analyze those errors and use them to find potential problems with the data.

# Model Tuning: Regularization
Overfitting errors can be reduced using regularization - a technique that helps evenly distribute weights among features.

# Model Tuning: Hyperparameter Tuning
Before we discuss how and when to tune the hyperparameters of a model, take a moment to distinguish between parameters and hyperparameters. 

# Model Tuning
So far, you've split your data, run your model, addressed errors, and tuned some hyperparameters, but you'd still like to see an improved performance. It's time to tune your training data and your feature set.

# Model Tuning: Feature Extraction
Not all features contribute to a model's forecasting power, and you can use feature extraction or feature selection to reduce these noisy or uninformative features. This video focuses on feature extraction.

# Model Tuning: Feature Selection
This focuses on feature extraction and how it can help you decide which features to include in your final model. 

# Model Tuning: Bagging/Boosting
Feature extraction and selection are relatively manual processes. This video covers bagging and boosting, which are automated or semi-automated approaches to determining which features to include.

# Knowledge 4 ( answers)
![Knowledge_Check_4_1](/The_Elements_of_Data_Science/images/Knowledge%20check%204.1.PNG)
![Knowledge_Check_4_2](/The_Elements_of_Data_Science/images/Knowledge%20check%204.2.PNG)

# CHAPTER - 5
# Model Evaluation and Model Productionizing
In this section of the course, we'll focus on the production phase of the machine learning pipeline. We'll review the cycle of machine learning projects, and examine how AWS services can help the storage, monitoring, and maintenance aspects of model production. 

# Introduction
In this section of the course, we'll focus on the production phase of the machine learning pipeline. We'll review the cycle of machine learning projects, and examine how AWS services can help the storage, monitoring, and maintenance aspects of model production. 

# Using ML Models in Production
This explores what is needed in order to get a machine learning model to production. First, we'll discuss the different aspects of production and then we'll cover some types of production environments. 

# Model Evaluation Metrics
we'll discuss how to quantify the overall performance of a particular machine learning algorithm using business metrics and analytical metrics.

# Cross-Validation
This explains cross-validation, a technique used to assess how the results of one model will generalize against a new data set. 

# K-Fold Cross-Validation
In this we will briefly introduce k-fold cross validation and discuss how, once again, the type of cross-validation you use depends on your business problem.

# Metrics for Linear Regression
This explores when to use linear regression, and what to consider when choosing a confidence interval.
 
# Using ML Models in Production: Storage
Different machine learning models require different types of storage. This video covers the pros and cons of different data storage formats for ML models in production. Other topics include model and pipeline persistence.

# Using ML Models in Production: Monitoring and Maintenance
In this, we’ll review the importance of monitoring and maintaining your machine learning models. 

# Using ML Models in Production: Using AWS
Here, we explore AWS's comprehensive ecosystem for building machine learning models.

# The AWS ML Ecosystem
ML Models at Scale with SageMaker

1.	Amazon sagemer ( ml model at scale with sagemaker )
2.	Amazon recognition ( automatic object recognition ) 
3.	Amazon comprehend( all about language )
4.	Amazon polly ( all about language )
5.	Amazon transcribe ( all about language )
6.	Amazon translate ( all about language)
7.	Amazon lex ( all about language )
8.	Amazon deeplens (ML hardware )

# Common Mistakes
This sections review common mistakes that occur during machine learning projects.

# Knowledge - 5 ( answers )
![Knowledge_Check_5_1](/The_Elements_of_Data_Science/images/Knowledge%20check%205.1.PNG)
![Knowledge_Check_5_2](/The_Elements_of_Data_Science/images/Knowledge%20check%205.2.PNG)
![Knowledge_Check_5_3](/The_Elements_of_Data_Science/images/Knowledge%20check%205.3.PNG)

--------------------------------------------------------------------E-N-D-------------------------------------------------------------------
