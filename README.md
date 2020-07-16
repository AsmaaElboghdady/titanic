Dataset: Titanic dataset
Mission: predicting if a passenger survived or not
Attributes: Mixed Categorical and Numeric 
Missing Values: Exist


Model used: Random Forest trees
Language: R
__________________________
Note:
It was wise in the preprocessing step to notice that certain Cabines have higher survivals than others,
so I did not exclude "Cabin" but transform it into numbers as factors weighting the prominent cabinet either for survival or death,
being in certain cabines may either increse weight of survival or death, with "Cabin" implied, the accuracy fitting the out of bagging was higher but lower with the test test. Accuracy on test was 73%.
when excluding "Cabin" at all, it increased to 76% predicting on test set lower on oob.
__________________________

