# ML

The field of study that gives computers the capability to learn without being explicitly programmed.

It is basically a process of training a piece of software called an algorithm or model, to make useful predictions from data. 

# Types of machine learning problems:
### 1.On basis of the nature of the learning “signal” or “feedback” available to a learning system
***Supervised learning:***

Some real-life examples are:

Image Classification: You train with images/labels. Then in the future you give a new image expecting that the computer will recognize the new object.

Market Prediction/Regression: You train the computer with historical market data and ask the computer to predict the new price in the future.

Two most common use cases of Supervised learning are: 

- Classification: Inputs are divided into two or more classes, and the learner must produce a model that assigns unseen inputs to one or more (multi-label classification) of these classes and predicting whether or not something belongs to a particular class. This is typically tackled in a supervised way.  Classification models can be categorized in two groups: Binary classification and Multiclass Classification. Spam filtering is an example of binary classification, where the inputs are email (or other) messages and the classes are “spam” and “not spam”.
- Regression: It is also a supervised learning problem, that predicts a numeric value and outputs are continuous rather than discrete. For example, predicting the stock prices using historical data.
            
***Unsupervised learning***

  🎶  Clustering: You ask the computer to separate similar data into clusters, this is essential in research and science.

  🎶  High Dimension Visualization: Use the computer to help us visualize high dimension data.

  🎶  Generative Models: After a model captures the probability distribution of your input data, it will be able to generate more data. This can be very useful to           make your classifier more robust.

Most common Unsupervised learning are:
            
            - Clustering: Here, a set of inputs is to be divided into groups. 
            
            - Density estimation: The task is to find the distribution of inputs in some space.
            
            - Dimensionality reduction: It simplifies inputs by mapping them into a lower-dimensional space. Topic modeling is a related problem, where a program is   given a list of human language documents and is tasked to find out which documents cover similar topics.

***Semi-supervised learning:***

Problems where you have a large amount of input data and only some of the data is labeled, are called semi-supervised learning problems. These problems sit in between both supervised and unsupervised learning.

***Reinforcement learning:***

A computer program interacts with a dynamic environment in which it must perform a certain goal (such as driving a vehicle or playing a game against an opponent). The program is provided feedback in terms of rewards and punishments as it navigates its problem space.

Terminologies of Machine Learning:`Model`  `Feature`  `Target (Label)`  `Training`   `Prediction`

***Machine learning implementations are classified into four major categories, depending on the nature of the learning “signal” or “response” available to a learning system.***

#### Basic Difference in ML and Traditional Programming?

 😊 Traditional Programming: We feed in DATA (Input) + PROGRAM (logic), run it on the machine, and get the output.

 😎 Machine Learning: We feed in DATA(Input) + Output, run it on the machine during training and the machine creates its own program(logic), which can be evaluated while testing.

#1.Data and It’s Processing:

### 1.1 Introduction to Data in Machine Learning
`          Data-----> information----->knowledge        `

![data](https://user-images.githubusercontent.com/90051406/199500943-835f14ec-db6d-479e-b42f-d4cfebd30a11.png)

***Different Forms of Data*** 

- Numeric Data : If a feature represents a characteristic measured in numbers , it is called a numeric feature.

- Categorical Data : A categorical feature is an attribute that can take on one of the limited , and usually fixed number of possible values on the basis of some qualitative property . A categorical feature is also called a nominal feature.

- Ordinal Data : This denotes a nominal variable with categories falling in an ordered list . Examples include clothing sizes such as small, medium , and large , or a measurement of customer satisfaction on a scale from “not at all happy” to “very happy”.
  
***Properties of Data – ***

Volume: Scale of Data. With the growing world population and technology at exposure, huge data is being generated each and every millisecond.

Variety: Different forms of data – healthcare, images, videos, audio clippings.

Velocity: Rate of data streaming and generation.

Value: Meaningfulness of data in terms of information that researchers can infer from it.

Veracity: Certainty and correctness in data we are working on. 

### 1.2 Understanding Data Processing
![data processing - Google Search](https://user-images.githubusercontent.com/90051406/199505267-dfaff941-9a0d-41a2-8a38-f4557a27e411.png)

### 1.3 Create Test DataSets using Sklearn

### 1.4 Data Preprocessing in Python
### 1.5 Data Cleaning
![datacIn1.png](https://user-images.githubusercontent.com/90051406/199507020-16858f6a-215b-4d83-bc54-f593b5ccf068.png)

data cleansing tools : `Openrefine`  `Trifacta Wrangler `   `TIBCO Clarity`    `Cloudingo`    `IBM Infosphere Quality Stage`
### 1.6 
### 1.7 
# Agents in Artificial Intelligence

# REad

**Artificial Intelligence and Machine Learning are likely to replace the current model of technology that we see these days, for example, traditional programming packages like ERP and CRM are certainly losing their charm.**

💭 Difference between AI & ML

💭 How we split data in Machine Learning?  

✨ Training Data: The part of data we use to train our model. This is the data that your model actually sees(both input and output) and learns from.

✨ Validation Data: The part of data that is used to do a frequent evaluation of the model, fit on the training dataset along with improving involved hyperparameters (initially set parameters before the model begins learning). This data plays its part when the model is actually training.

✨ Testing Data: Once our model is completely trained, testing data provides an unbiased evaluation. When we feed in the inputs of Testing data, our model will predict some values(without seeing actual output). After prediction, we evaluate our model by comparing it with the actual output present in the testing data. This is how we evaluate and see how much our model has learned from the experiences feed in as training data, set at the time of training.

💭 What does exactly learning mean for a computer? 

A computer is said to be learning from Experiences with respect to some class of Tasks if its performance in a given task improves with the Experience. 
 
💭 How does ML work?

Gathering past data in any form suitable for processing. The better the quality of data, the more suitable it will be for modeling

Data Processing – Sometimes, the data collected is in raw form and it needs to be pre-processed. Example: Some tuples may have missing values for certain attributes, and, in this case, it has to be filled with suitable values in order to perform machine learning or any form of data mining. Missing values for numerical attributes such as the price of the house may be replaced with the mean value of the attribute whereas missing values for categorical attributes may be replaced with the attribute with the highest mode. This invariably depends on the types of filters we use. If data is in the form of text or images then converting it to numerical form will be required, be it a list or array or matrix. Simply, Data is to be made relevant and consistent. It is to be converted into a format understandable by the machine

Divide the input data into training, cross-validation, and test sets. The ratio between the respective sets must be 6:2:2

Building models with suitable algorithms and techniques on the training set.

Testing our conceptualized model with data that was not fed to the model at the time of training and evaluating its performance using metrics such as F1 score, precision, and recall.

1.Linear Algebra

2.Statistics and Probability

3.Calculus

4.Graph theory

5.Programming Skills – Languages such as Python, R, MATLAB, C++, or Octave
