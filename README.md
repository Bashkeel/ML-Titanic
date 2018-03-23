# Kaggle Competition | Titanic: Machine Learning From a Disaster

![](header.png)

### Competition Description
> The sinking of the RMS Titanic is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

> One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

> In this challenge, we ask you to complete the analysis of what sorts of people were likely to survive. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.

> **Goal** <br>
>It is your job to predict if a passenger survived the sinking of the Titanic or not. 
For each PassengerId in the test set, you must predict a 0 or 1 value for the Survived variable.

> **Metric** <br>
>Your score is the percentage of passengers you correctly predict. This is known simply as "accuracy”.

## **Final Score**: 0.78947 (Top 31%)
 
<br>

 
### Steps taken in this Notebook 
1. Data Wrangling 
    * Loading the datasets with `pandas`
    * Visualizing missing data with `missingno` 
    * Checking correlation between survival and individual factors  
<br> 

2. Feature Engineering
    * Feature engineering of new columns
        * Passenger Title
        * Family Size
        * Travelling Alone?  
<br> 

3. Imputing Missing Data Values
    * Randomizing the two missing Embarked values
    * Imputing the missing fare value using the average fare paid by each Pclass
    * Testing various ML Regression algorithms to predict age
        * Linear Regression
        * Bayesian Ridge
        * Multilayer Perceptron (MLP)
        * Decision Tree
        * Bagging
    * Using Multilayer Perceptron (MLP) to predict the missing age values
<br> 

4. Predict Survival
    * Test various ML Classifier algorithms to predict Survival
        * Logistic Regression
        * Support Vector 
        * Decision Tree 
        * Random Forest 
        * Adaptive Boosting 
        * Multilayer Perceptron (MLP) 
        * K-Nearest Neighbours (KNN) 
    * Using MLP to predict Survival
    * Formatting output for submission
<br> 

### Required Libraries
* [`numpy`](http://www.numpy.org/)
* [`pandas`](https://pandas.pydata.org/)
* [`missingno`](https://github.com/ResidentMario/missingno)
* [`seaborn`](http://seaborn.pydata.org/)
* [`matplotlib`](https://matplotlib.org/)
* [`random`](https://docs.python.org/2/library/random.html)
* [`scikit-Learn`](http://scikit-learn.org)
