# Datasets
This repository includes nine synthetic and 28 real-world datasets for evaluating machine learning algorithms. All the real-world datasets were obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php). The datasets are provided in two kinds of formats, MAT files for Matlab, and text files:

* Datasets stored in MAT files have the following variables:
  * Xtr - Training data. It is a matrix of size D x Ntrain.
  * Ytr - Training class labels. It is a vector of size 1 x Ntrain.
  * Xtt - Test data. It is a matrix of size D x Ntest.
  * Ytt - Test class labels. It is a vector of size 1 x Ntest.
  * info - Structure with information about the dataset.

* Datasets stored in TXT files are organized as follows:
  * train.txt - Training data. The first column is the class label, and the remaining columns are the features.
  * test.txt - Test data. The first column is the class label, and the remaining columns are the features.
  * info.txt - Information about the dataset.
