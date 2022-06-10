## Assignment 01

Task: *Introduce changes to the starter code for final assignment 1 to show the effect on one or more alterations on feature selection, extraction, and transformation.*

#### Changes Introduced:
* HashingVectorizer
	* stop_words=english
	* n_features= 2 ** 10  
* StandardScaler
	* std=false
* TfidfTransformer
	* sublinear_tf=true

Before introducing any changes, the models performed as follows:
![](graphs/original.png)

The graphs representing the performance are as follows:
###### stop_words=english 
![](graphs/english_dict.png)
###### n_features= 2 ** 10
![](graphs/reduced_n_features.png)
###### std=false
![](graphs/std_false.png)
###### sublinear_tf=true
The Naive Bayes model erred, showing that Input X must be non-negative:
![](graphs/sublinear_tf_true.png)


For easier comparison, here I show the ROC plots and Accuracy comparison between all iterations:

###### ROC train set
![](graphs/ROC_train.png)
###### ROC test set
![](graphs/ROC_test.png)
###### Accuracy comparison
![](graphs/accuracy_comparison.png)

