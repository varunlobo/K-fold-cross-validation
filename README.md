# K-fold-cross-validation
Implementation of k fold cross validation.


## In this notebook we demonstrate using the k-fold cross validation method to evaulate and predict the effectiveness of our model. We used linear regression to predict the housing price from the boston dataset we obtained from kaggle.

For our example, we divide our training dataset into 10 parts (10 folds i.e. k=10). We then iteratively evaluate our model (in our case Linear Regression) over the other k-1 parts and test it with k=1,2,...10. This gives us an understanding of the effectiveness of our model. The error obtained is the average error obtained over all k folds. The image below shows dividing of data into 10 folds. 

![kfolds](https://user-images.githubusercontent.com/114509328/202322545-24deb2c2-e439-44b4-9120-810a15f74419.jpg)
