# datasets
Synthetic and real-world atasets for evaluating machine learning algorithms. The datasets are provided in two kind of formats, MAT files for Matlab, and text files.

Datasets stored in a .MAT file have the following variables:
* Xtr - Training data. It is a matrix of size D x Ntrain.
* Ytr - Training class labels. It is a vector of size 1 x Ntrain.
* Xtt - Test data. It is a matrix of size D x Ntest.
* Ytt - Test class labels. It is a vector of size 1 x Ntest.
* info - Structure with information about the dataset.

Datasets stores in .TXT file are ornaized as follows:
* train.txt - Training data. The fist column is the class label, and the remaining columns are the features.
* test.txt - Test data. The fist column is the class label, and the remaining columns are the features.
* info.txt - Information about the dataset.
