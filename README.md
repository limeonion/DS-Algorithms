# Algorithms and Models for Data Analysis - Learning and Prediction

In this lab, three algorithms have been used - Linear Regression, K- Nearest Neighbors and K means clustering on the datasets and performance of model has been tested in each case.

The datasets used - NHL Top 100 players, German Credit data(both available at Kaggle Database) and Pew Research Center Data on Gaming, Broadband and Jobs.
 K-means, Linear regression, k-nearest neighbours

Data-set used: Iris data-set will be used to explore a vignette that analyses the data-set using k-means clustering that will be used further. 
     Input: Iris data; Output: Iris clusters; Process: K-means 

Activity 1: Linear Model
          Data-set: National Hockey League data
          NHL top 100 data. Fitting a linear (regression) model to this data. Assists on Y-axis and Goals on X-axis.
a. After the initial fitting, evaluate the fit by noting the R 2 and p values of the fit.
b. Change the model so that it line is forced through Wayne Gretzky. Note the R 2 and p values of
the fit. This will another line or if you prefer another plot.
c. Now add the data for another player Patrick Kane (he is a current player). You need to get the
data for form online sources. Create a new chart with this addition and force the line through
Kane but not Gretzky. Note R 2 and p values of the fit.
d. Make all the model go through (0,0) and create new models. Note R 2 and p values of the fit.
e. Create a table of model names (reference), R 2 and p values of the fit. Interpret your results.

  Input: NHL Top 100 players; Output: Fitted Linear models; Process: "lm" model of R, summary of metrics in a table and interpretation of the results.
  
  
Activity 2: K-nn classification with credit data
  Tabluation of the results for various K. Also, varying the sizes of test and training sets.
  Data source: https://buffalo.box.com/s/jm1hki9hbnlm4kzfkaimkzilys3dm8dg
  

Activity 3: K-means clustering with Pew Data
   Pew Research Center has been collecting data for a long time about social issues using
survey approach. Studying their home page here and the types of questions they try to answer
using the data sets collected and analyzed using scientific methods. We are especially
interested in look at the data PRC collected about Gaming, Jobs and Broadband. We cleaned the
data set.We will use at least 5 variables (columns) to cluster the data and
understand the data. Interpreting the cluster characteristics for various K = 3, 5.

