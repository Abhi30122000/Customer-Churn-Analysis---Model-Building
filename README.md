❑Exploratory Data Analysis is an approach to
analyse the datasets to summarize their
main characteristics in form of visual
methods.
❑ EDA is nothing but an data exploration
technique to understand various aspects of
the data.
❑ The main aim of EDA is to obtain confidence
in a data to an extent where we are ready to
engage a machine learning model.

❖ EDA is important to analyse the data it’s a
first steps in data analysis process.
❖ EDA give a basic idea to understand the data
and make sense of the data to figure out the
question you need to ask and find out the
best way to manipulate the dataset to get
the answer of your question.
❖ Exploratory data analysis help us to finding
the errors, discovering data, mapping out
data structure, finding out anomalies.
❖ Exploratory data analysis is important for
business process because we are preparing
dataset for deep through analysis that will
detect you business problem.
❖ EDA help to build a quick and dirty model,
or a baseline model, which can serve as a
comparison against later models that you
will build.

Data Sourcing is the process of gathering data
from multiple sources as external or internal
data collection.
There are two major kind of data which can
be classified according to the source:
1. Public data 2. Private data
Public Data:- The data which is easy to access
without taking any permission from the agencies
is called public data. The agencies made the data
public for the purpose of the research. Like
government and other public sector or
ecommerce sites made there data public.
Private Data:- The data which is not available
on public platform and to access the data we
have to take the permission of organisation is
called private data. Like Banking ,telecom ,retail
sector are there which not made their data
publicly available.

• After collecting the data , the next step is
data cleaning. Data cleaning means that you
get rid of any information that doesn’t need
to be there and clean up by mistake.
• Data Cleaning is the process of clean the data
to improve the quality of the data for further
data analysis and building a machine
learning model.
• The benefit of data cleaning is that all the
incorrect and irrelevant data is gone and we
get the good quality of data which will help
in improving the accuracy of our machine
learning model.
The following are some steps involve in Data
Cleaning:
 Handle Missing Values
 Standardisation of the data
 Outlier Treatment
 Handle Invalid values

 Standardization/
Feature Scaling
Feature scaling is the method to rescale the values
present in the features. In feature scaling we convert
the scale of different measurement into a single
scale. It standardise the whole dataset in one range.
Importance of Feature Scaling:- When we are
dealing with independent variable or features that
differ from each other in terms of range of values or
units of the features, then we have to
normalise/standardise the data so that the difference
in range of values doesn’t affect the outcome of the
data.

Standard scaler ensures that for each feature, the mean is
zero and the standard deviation is 1,bringing all feature to the
same magnitude. In simple words Standardization helps you
to scale down your feature based on the standard normal
distribution

Outliers are the most extremes values in the data. It is a
abnormal observations that deviate from the norm.
Outliers do not fit in the normal behaviour of the data.
Detect Outliers using following methods:
1.Boxplot 2. Histogram 3. Scatter plot
4.Z-score
5. Interquartile range(values out of 1.5 time of IQR)
Handle Outlier using following methods:-
1.Remove the outliers.
2.Replace outlier with suitable values by using following
methods:-
• Quantile method
• Interquartile range
3.Use that ML model which are not sensitive to outliers
 Like:-KNN,Decision Tree,SVM,NaïveBayes,Ensemble
methods

Segmented Univariate Analysis allow you to compare
subset of data it help us to understand how the
relevant metric varies across the different segment.
The Standard process of segmented univariate
analysis is as follow:
• Take a raw data
• Group by dimensions
• Summarise using a relevant metric like mean
,median.
• Compare the aggregate metric across the
categories.
