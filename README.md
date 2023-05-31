# Airline insurance claim prediction using Machine learning
Abstract 

Now a day's Data is playing a central role and is carrying the big asset in the insurance industry. 
In today's journey insurance industry has a vital role. Insurance transporters have access to more 
information than ever before. From the past 700+ years in the insurance industry we can consider 
the three major eras Starting from 15th century to 1960, industry followed the manual era, 
from1960s to 2000 we are in the systems era, now we are in digital era i.e. 2001-20X0.The 
highest corporate object in all three eras is that the fundamental insurance industry has been 
determined by believing the data analytics in adopting the changing technologies to better and 
keep the ways and keep capital together. In advanced analysis the main challenge is the 
analytical models and algorithms which are being insufficient to support insurers; only by 
machines we can overcome this challenge. This study suggests using decision tree, support 
vector machine, kernel approx, random forest classifier and lasso regression as data mining 
techniques and classification algorithms to predict the airlines insurance claim.
Keywords: Machine Learning, Digital Era, Client Lifetime Value (CLV).

Dataset –
Datasets which is used is project has been collected from kaggle datasets. Columns present in 
this datasets are Age, Agency_Code, Type, Claimed, Commision, Channel, Duration, Sales, 
Product Name, Destination. This dataset contains information about airline insurance climb 

➢Preprocessing 
In Machine Learning, data preprocessing refers to the process of preparing raw data to 
make it appropriate for the construction and training of Machine Learning models. Here 
the job prediction datasets are pre processed so as to improve the working of the system, 
as in this process the raw data is processed into proper data.
➢ Extracting features 
Feature Extraction is a technique for reducing the amount of features in a dataset by 
generating new ones from existing ones. The original set of features should then be able 
to summarise the majority of the information in the new reduced set of features.
➢ Trained data & test data 
A training set is a subset of a larger data set that is used to fit a model for predicting or 
classifying values that are known in the training set but unknown in the rest of the data. 
The training set is used in conjunction with the validation and/or test sets to assess 
various models.
A test set is a subset of a data set that is used in data mining to evaluate the likely future 
performance of a single prediction or classification model that has been chosen from a 
pool of competing models based on its performance with the validation set.
➢ Classification 
A data mining function called classification allocates objects in a collection to desired 
groups or classes. Classification's purpose is to correctly anticipate the target class for 
each case in the data. For example, a categorization model could be used to categorise 
loan applicants as having low, medium, or high credit risks
➢ Performing Algorithm 
Here we will be performing various classification algorithm for finding the accuracy and 
finding the error. Here we will also find specificity and sensitivity for comparison of 
algorithms.
➢ Packages –
Packages used in job prediction are as follows –
1) Pandas
2) Numpy
3) Matplotlib
4) Sklearn

Methodology 

In this study, we have implemented some of the classifications algorithm for job 
prediction system. Here we have implemented classification algorithms like using 
SGD, decision tree, support vector machine, kernel approx, random forest 
classifier and lasso regression. In this system we have found accuracy rate and 
error rate of each and every algorithm for the comparative study of each 
algorithms.
i. SGD Algorithm 
Stochastic gradient descent (often abbreviated SGD) is an iterative method 
for optimizing an objective function with suitable smoothness properties 
(e.g. differentiable or sub-differentiable). It can be regarded as a stochastic 
approximation of gradient descent optimization, since it replaces the actual 
gradient (calculated from the entire data set) by an estimate thereof 
(calculated from a randomly selected subset of the data).
ii. SVM Algorithm 
The Support Vector Machine, or SVM, is a popular supervised learning 
technique that maybe used to solve classification and regression issues. 
However, it is mostly utilised in Machine Learning for Classification 
difficulties. The SVM algorithm’s purpose is to find the optimum line or 
decision boundary for categorising n-dimensional space into classes so that 
additional data points can be readily placed in the correct category in the 
future. A hyperplane is the name for the optimal choice boundary. 
iii. Decision Tree 
A decision tree is a flowchart like structure in which each internal node 
represents a “test” on an attribute (for example, whether a coin flip will 
come up heads or tails), each branch reflects the test’s conclusion, and each 
leaf node represents a class label. 
iv. Kernel Approximation 
This sub-module contains functions that approximate feature mappings that 
correlate to specific kernels, as used in Support Vector Machine. The 
following feature functions alter the input in non-linear ways, which can be 
used as a foundation for linear classification or other methods.
v. Lasso Regression 
Lasso (least absolute shrinkage and selection operator) is a regression 
analysis approach in statistics and machine learning that does both variable 
selection and regularisation to improve the predictability and interpretability 
of the final statistical model.
vi. Random Forest Algorithm 
Random forest is a supervised machine learning algorithm that is commonly 
used to solve classification and regression problems. It creates decision trees 
from various samples, using the majority vote for classification and the 
average for regression

Conclusion –

After finding all the accuracy and error values, finally we have concluded that 
Random Forest is the best algorithm for predicting the values. As Random Forest 
provides greater prediction accuracy compared to other machine learning models.
