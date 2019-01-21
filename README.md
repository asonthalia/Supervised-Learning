# Supervised-Learning

This repository will help you in understanding the concepts of supervised learning. 

KNN classification -

1. This kind of a classifier is a supervised lazy classifier.
2. It's called a lazy classifier because it does not classify any point upto the prediction phase, it just tries to mug up 
   the data in some sense.
3. The KNN classifier can have really complicated decision boundaries unlike random forest classifiers.
4. This is also a con because these models will tend to overfit the data too much.
5. KNN is a local classifier which means that outliers will kill it's performance significantly.
6. The order of computation of KNN is ^2, the distance calculation, which makes it computationally very expensive when large datasets
   are present.
7. If number of columns are large a PCA or SVD is required.
   
PROS -

1. Can adjust to complex decision boundaries
2. Excellent for smaller data sets

CONS -

1. n^2 complexity makes it slow
2. Bad for real-time prediction
