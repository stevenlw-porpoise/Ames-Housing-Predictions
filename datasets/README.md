#### Files:
* test.csv, train.csv - Original data files
* test_cleaned, train_cleaned.csv - Filled missing values, removed some features and added others compared to original. Some ordinal encoding done. Outputs of data_wrangling.ipynb
* base_residuals.csv, ridge_residuals.csv, enet_residuals.csv - training set residuals from a base, ridge, and elastic net model.
Note that due to a data gathering error one row and one column (Sale Condition) is missing from the original data set.
