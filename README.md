# PROBLEM DESCRIPTION

Imbalanced datasets are a huge problem to deal with. The high number of data points of one class makes it harder for the classifier to learn about the minority classes. Till today, there has been no "STATE-OF-THE-ART" technique to deal with the problem of learning from imbalanced datasets.

# THE ACCURACY TRAP

Evaluation or Scoring metrics plays a huge role in understanding how the model is performing. Accuracy_Score is not a good metric to evaluate classification modfels in imbalanced datasets. This is because even if the model learns to predict only the majority class, we will still end up with a pretty good accuracy score.

# BETTER EVALUATION METRICS

 So a better alternative will be to look at the confusion matrix. Evaluation metrics suck as precision, recall and F1 score will be good alternatives too.
