## Predicting Iris Flower Species using OOP framework

**Classifying Iris flowers into three species, by creatig a classification model that learns from the historical Iris species data. In addition, we will identify the correlation of flower species with the different variables like sepalLength, sepalwidth,  and bring out actionable insights from the existing dataset.**
***

*STATING THE ASSUMPTIONS:*


*The data is a reflection of Iris flower dataset collated a few years ago and it is assumed that it is a reflection of the existent Iris flower species. We do not take into account the dependance of Iris flower species on the location or demography.*

*It includes three iris species with 50 samples each as well as some properties about each flower. One flower species is linearly separable from the other two, but the other two are not linearly separable from each other.*

The columns in this dataset are:

1 *Id*

2 *SepalLengthCm*

3 *SepalWidthCm*

4 *PetalLengthCm*

5 *PetalWidthCm*

6 *Species*

*LAYING DOWN THE GROUNDWORK*
***
- What are we analyzing?

**In the first step, we will be analyzing the correlation between the different variables of the dataset and write down the inferences. These variables include SepalLength, SepalWidth, PetalLength and PetalWidth.**

- What our variables mean?

**The different variables signify the different attributes a flower can have.**

- Why are we analyzing this data set?

**To develop a working classification model that can be deployed and used to predict the species of a new flower on the basis of its basic features and thus aid in the flower classification process.**

### Summary of Model development
***

*a) How did the baseline model perform and which algorithm resulted in an overall best performance?*

****

**1. Built a baseline model (Logistic Regression), with an average recall of 0.97**

**2.Out of all the models tested, Gradient Boosting shows the highest recall, precision and f1 score of 1**

