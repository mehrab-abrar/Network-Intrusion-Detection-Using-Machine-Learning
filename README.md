# Network Intrusion Detection Using Machine Learning

In this project, we explore the performances of Machine Learning (ML) classification models in detecting network intrusion through. The project includes a binary dataset with class imbalance, a common issue in real-world datasets.

# Stratified K-fold split

This project addresses class imbalance during data splitting for training and testing by employing a stratified K-fold split. Stratified K-fold split involves dividing the dataset into "K" equally sized subsets while maintaining the proportion of instances from each class in every subset. This method ensures that each subset represents the overall class distribution of the dataset accurately.

# Why should we use Stratified K-fold 

Let's say you have a dataset for binary classification where 90% of the samples belong to Normal Data, and only 10% belong to Abnormal Data. Without stratified k-fold cross-validation, there's a risk that during the random splitting of the data into folds (using train_test_split()), one or more folds may end up with a disproportionately low representation of Abnormal samples. This can lead to biased model evaluation, where the model may not adequately learn to classify the minority class or Abnormal Data.

# Randomized Cross Validation

This project fine-tunes the hyperparameters of six distinct ML models: Logistic Regression, Random Forest, XGBoost, K-Nearest Neighbor, Support Vector Machine, and Multi-layer Perceptron by using Randomized cross validation.

Check the Jupyter Notebook file to access the full project code.

