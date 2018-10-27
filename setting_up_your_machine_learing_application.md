# Setting up your machine learing application 

## Splitting of the data set 

![data](images/data_set.png)

* Partition size 60/20/20 %
* Make sure dev and test come form same distribution
    * Training set from webpages
    * Dev and test set from app users

## Fields

it is important to remove all columns from the dataset that influences negative a prediction for the incoming dataset

* ID 
* ...

## Data from different distrubtions

if you have different data distrubtions then use your own data for dev and test partition and your other data for the train partition (A/B set)

![data from different distrubtions](images/data_from_different_distrubtions.png)