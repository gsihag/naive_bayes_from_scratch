# naive_bayes_from_scratch
this code represents naive bayes algorithm built from scratch. It can also work well with missing values.
 This code also works for multi-class classification problems (e.g. democrat/republican/independent). 
 Calculate P(E1|CL0)P(E2|CL0)P(E3|CL0)...P(E#|CL0) * P(CL0) and
 P(E1|CL1)P(E2|CL1)P(E3|CL1)...P(E#|CL1) * P(CL1) and
 P(E1|CL2)P(E2|CL2)P(E3|CL2)...P(E#|CL2) * P(CL2), etc. and 
 predict the class with the maximum result. 
 E is an attribute, and CL means class.
 Only need class prior probability and likelihoods to make a prediction
 (i.e. the numerator of Bayes formula) since denominators are 
 same for both the P(CL0|E1,E2,E3...)*P(CL0) and 
 P(CL1|E1,E2,E3...)*P(CL1), etc. cases where P means "probability of" 
 and | means "given".
  
 Required Data Set Format for Disrete Class Values
 Columns (0 through N)
 0: Instance ID
 1: Attribute 1 
 2: Attribute 2
 3: Attribute 3 
 ...
 N: Actual Class
 
 This program then adds 1 additional columns for the test set.
 N + 1: Predicted Class
