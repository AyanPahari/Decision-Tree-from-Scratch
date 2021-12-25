
# Decision Tree from Scratch

Implemented a Decision Tree from Scratch using binary univariate 
split, entropy and information gain. 

- Evaluated it's performance using 10 folds cross validation
- Improvement strategies:

        - Use Gini index instead of entropy
        - Prune the tree after splitting for better generalization




## Dataset

Wine-Dataset
## Accuracies

- Accuracy of Initial Implementation using Entropy and Information Gain

        1. K-Fold(K=10) Cross Validation without Random Sampling Accuracy: 74.90%
        2. K-Fold(K=10) Cross Validation with Random Sampling Accuracy: 84.06%

It can be seen by the accuracies that Cross Validation with random sampling works much better than without random sampling, as it randomly splits the data into training and testing this will ensure that the model will not be affected by any inbuilt bias in the dataset.

- Accuracy of Improved Implementation

        1. Gini Index instead of Entropy(K-Fold Cross Validation with Random Sampling) Accuracy: 83.32%
        2. Pruning the Tree to a certain depth and using min sampling threshold(K-Fold Cross Validation with Random Sampling) Accuracy : 84.22%
Using Gini index instead of Entropy the accuracy doesn’t seem to change that much, but the structure of the tree and the split values definitely have changed.

After Pruning the tree the accuracy came out to be slightly better than the previous approach but still not a huge improvement.
## Authors

- [@AyanPahari](https://github.com/AyanPahari)

