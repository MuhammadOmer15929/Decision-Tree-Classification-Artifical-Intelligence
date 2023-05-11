# Decision-Tree-Classification-Artifical-Intelligence
Perform Decision Tree Classification on this dataset using SKLEARN library. Answer the
following questions:
• Load the "balance-scale.csv" dataset into a pandas dataframe.
• Add column names. The column names are [‘Class’, “left_weight”, “left_distance”,
‘right_weight’, ‘right_distance’]
• Perform exploratory data analysis on the loaded dataset. This includes finding the number of
unique values in the each columns, and removing null values (if any). Also, find out the mean,
median, and standard deviation of the numerical columns.
• Choose the independent variables as features and the dependent variable as the label.
• Convert categorical data to numerical data using label encoding.
• Split the dataset into training and testing sets with a 70:30 ratio.
• Build two decision tree classification models, one with criterion 'gini' and the other with
criterion 'entropy'.
• Train both models on the training set and make predictions on the testing set.
• Calculate the accuracy score of both models and compare them.
• Also calculate the precision, recall and f-1 score using SKLEARN library.
• Draw the confusion matrix.
