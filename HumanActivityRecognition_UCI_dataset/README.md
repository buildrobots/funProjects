# Human Activity Recognition using Smartphone Sensors

### 1. Introduction
Smartphones are quickly becoming a ubiquitous part of life in the world. Their embedded
sensors have the ability to record a significant amount of data about peoples’ movement.
Many smartphone applications already use that data to estimate basic fitness statistics,
such as daily step count. However, the simplistic metrics that these applications produce
are a poor method of assessing a person’s activity level. As a result, many people have
turned to wearable devices to track their fitness activities. However, smartphone
technology is improving, and so are techniques for using the data that smartphones gather.
If a phone could accurately assess a person’s daily activities, smartphone applications
could easily replace wearable fitness devices as a method of fitness tracking.


### 2. Project
Develop and test different machine learning methods to predict the activity that a person is
undertaking, based on signals from that person’s cell phone. The input to each of the
algorithms is a set of summaries of accelerometer and gyroscope signals and the output of
each algorithm is (a prediction of) the activity being performed when those signals were
recorded. While maximizing the accuracy of your predictions is the foremost goal, you also
have to pay attention to the number of features each method requires to obtain high
accuracy. Data requirements are of particular importance for smartphones, since their
capacity for transmitting, receiving, and storing data is limited. 

We would consider a method successful if it either:

(a) obtains better accuracy than previous methods, or
(b) obtains accuracy similar to that of previous methods but uses fewer features.

### 3. Data
The dataset on which you should test your methods is courtesy of the UCI Machine Learning.

**Repository**

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

It contains sumaries of accelerometer and gyroscope readings from waist-worn cell phones
by 30 volunteers while performing different activities. The data contain 10,299 observations
with subject-level). There are, altogether, 561 features in the data set; these are primarily
based on the 3-axial linear acceleration and 3-axial angular velocity. The response variable isthe activity that an individual was performing when the readings were obtained. 

**Categories**
Laying, 
Sitting, 
Standing, 
Walking, 
Walking Downstairs (WD), and 
Walking Upstairs(WU)


Each observation of the data set contains information regarding one sample window – a
segment of continuous time that a particular person spent doing a particular activity. The
signals from those windows were processed using various filtering techniques. The features
in the data set are summaries of those processed time-domain signals (captured at a constant
rate of 50Hz). For example, the feature set includes the mean, standard deviation, and
skewness of the gravity acceleration signal.

In preparation for your modeling, you should split the data as follows:

**training**: 5,147 observations
**validation**: 2,206 observations
**test**: 2,947 observations

### 4. Models to develop

KNN, 
Softmax regression, 
SVM

### 5. Required content in the report
- code
- Full paper (feature engineering, models, results, benchmark, error analysis and future work,
discussion, ..)
