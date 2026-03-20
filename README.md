Confusion matrix breakdown: 
  21 true negatives: actual not fire, predicted not fire
  1 false positive: actual not fire, predicted fire
  1 false negative: actual fire, predicted not fire
  26 true positives: actual fire, predicted fire

Classification report:
  0.0 = not fire
  1.0 = fire
  
  For class 0.0, it is correct 95% of the time.
  For class 1.0, it is correct 96% of the time.
  
  Recall 0.95 for 0.0 means it caught 95% of the actual not fire cases.
  Recall 0.96 for 1.0 means it caught 96% of the actual fire cases.

F1-score:
  A combined balance of precision and recall.

Support:
  How many true examples of that class were in the test set.

Table breakdown: 
  actual = the true class, what the original data was.
  predicted_probability = the model’s estimated probability that the row is fire.
  predicted_class = final prediction after applying the threshold, usually:
    probability >= 0.5 → predict 1
    probability < 0.5 → predict 0
