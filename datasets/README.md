#### Files:
* test.csv, train.csv - Original data files
* test_cleaned, train_cleaned.csv - Filled missing values, removed some features and added others compared to original. Some ordinal encoding done. Outputs of data_wrangling.ipynb
* base_residuals.csv, ridge_residuals.csv, enet_residuals.csv - training set residuals from a base, ridge, and elastic net model.

The dataset was given as split in to a training set (2051 rows) and test set (878 rows).
Note that due to a bug one row and one column (Sale Condition) is missing from the original data set.
