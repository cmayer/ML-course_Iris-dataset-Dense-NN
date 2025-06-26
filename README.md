# Simple solution for Iris dataset classification problem neural network and fully connected layers.

The Iris dataset is a classic and widely used dataset in machine learning and statistics. It was introduced by the British statistician Ronald A. Fisher in 1936 in his paper ["The use of multiple measurements in taxonomic problems"](https://onlinelibrary.wiley.com/doi/10.1111/j.1469-1809.1936.tb02137.x). The dataset contains 150 samples from three species of the Iris flower: Iris setosa, Iris versicolor, and Iris virginica. Each sample includes four numerical features: sepal length, sepal width, petal length, and petal width (all in centimeters). The goal is typically to classify the species based on these measurements.

Despite the fact that the dataset is rather small, it is possible for most reasonable train/test splits to achieve good classification results with a wide range of classifiers.

Here we use a neural network with one hidden layer to solve the classification problem with high prediction accuracies.

First create a conda environment to tensorflow, sklearn, etc. For the workshop it we have included also the software needed for other projects. You can use miniforge, mamba or Anaconda for this. I am using miniforge, since for Anaconda a license might be neede.

```
conda env create -f environment-ML-St-Andrews.yml
```

Now open the iris-dataset-with-NNs.py file in a text editor and try to understand the code.

The neural network was kept as simple as possible, with only one hidden layer.

Run the classification analyis by execting:
```
python3 iris-dataset-with-NNs.py
```

You could test the effect of the following modifications:
- add a second hidden layer
- change the number of neurons in the hidden layer
- change the learning rate for the Adam optimizer
- Test tanh and sigmoid as alternatives to the relu activation function.


