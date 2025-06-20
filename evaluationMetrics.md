# FineTuningBERT

This model uses the compute_metrics function to evaluate performance during and after training. The following metrics were computed:

Accuracy: Measures the proportion of correct predictions.
Example Output: test_accuracy printed during evaluation steps.

F1 Score (Weighted): Balances precision and recall for imbalanced datasets.
Helps assess model performance across both classes.

Precision: Proportion of correctly predicted positive observations.
Useful when false positives are costly.

Recall: Proportion of correctly predicted positive samples among all actual positives.
Useful when false negatives are costly.

Confusion Matrix: Plotted using seaborn to visualize true vs. predicted labels.

Each of these was displayed for the training, validation, and test sets.
