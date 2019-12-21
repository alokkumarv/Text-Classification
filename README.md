# BBC-Dataset-News-Classification

Consists of 2225 documents from the BBC news website corresponding to stories in five topical areas from 2004-2005.

Class Labels: 5 (business, entertainment, politics, sport, tech)


# Files Description

* bbc-txt.csv: csv file containing "text" and "Category" as columns. "text" column represent news article and "Category" represents news category among business, entertainment, politics, sport, tech.


* BBC Text Classification.ipynb: jupyter notebook 


# Method

Divided the feature extracted dataset into two parts train and test set. Train set contains 1557 examples and Test set contains 668 examples. 

# Result

Below table shows the result on test set

Model | Accuracy
--------- | ---------
MultiClassNaiveBayes | 0.95
KNN  | 0.92
