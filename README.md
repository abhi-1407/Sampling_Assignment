
# Sampling Assignment 102053017


In this I have tried applied 5 different ML models to a credit card dataset,which are as follows:

1)LogisticRegression 

2)DecisionTreeClassifier

3)RandomForestClassifier

4)SVC

5)ExtraTreesClassifier

##
The following formula has been applied:
n = (Z^2*(p(1 – p))/(m^2))

Where,
n is the sample size,
Z is the z-value,
p is the proportion of population,
m is the margin of error

I have chosen a Z value of 2.57(99% population) and a margin of error value of 0.05

##
The sampling technique used are:

1)RandomUnderSampler

2)RandomOverSampler

3)ADASYN

4)TomekLinks

5)NeighbourhoodCleaningRule

##
And here is the accuracy of the different models on different sample 

	     Sampling1   Sampling2    Sampling3    Sampling4   Sampling5
    M1    0.6258       0.9806       0.9806       0.9806       0.9806   

    M2    0.5032       0.9806       0.9806       0.9806       0.9677   

    M3    0.6065       0.9806       0.9806       0.9806       0.9806    

    M4    0.6387       0.9806       0.9806       0.9806       0.9806   

    M5    0.7226       0.9806       0.9806       0.9806       0.9806   



##


The maximum accuracy obtained was from ExtraTreesClassifier with accuracy of 0.929

##


