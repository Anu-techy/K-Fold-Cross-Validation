**K-Fold Cross-Validation** is one of the most popular techniques to evaluate how well your model generalizes to unseen data.

It’s a technique that:

      Splits your dataset into K equal-sized parts (folds)

      Trains the model on K−1 folds

      Tests it on the remaining fold

      Repeats this process K times, each time using a different fold as the test set

      Averages the evaluation scores (accuracy, AUC, etc.) across all K runs

**Why use K-Fold?**

Gives you a more reliable estimate of model performance

Reduces risk of overfitting to a single train-test split

Works great on small to medium datasets

**Stratified K Fold Cross Validation**

It's just like regular K-Fold, but it ensures that each fold has the same proportion of each class as the original dataset.

This helps your model get a more balanced view during training/testing in each fold.

