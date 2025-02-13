# Digit_recognizer_CNN
Deep Learning
------------------------
| Description         |
------------------------
MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

In this competition, your goal is to correctly identify digits from a dataset of tens of thousands of handwritten images. We’ve curated a set of tutorial-style kernels which cover everything from regression to neural networks. We encourage you to experiment with different algorithms to learn first-hand what works well and how techniques compare.

More details about the dataset, including algorithms that have been tried on it and their levels of success, can be found at http://yann.lecun.com/exdb/mnist/index.html.

------------------------
| Evaluation           |
------------------------

Goal
The goal in this competition is to take an image of a handwritten single digit, and determine what that digit is.
For every in the test set, you should predict the correct label.
Metric
This competition is evaluated on the categorization accuracy of your predictions (the percentage of images you get correct).

------------------------
| Dataset Description  |
------------------------

The data files train.csv and test.csv contain gray-scale images of hand-drawn digits, from zero through nine.

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255, inclusive.

The training data set, (train.csv), has 785 columns. The first column, called "label", is the digit that was drawn by the user. The rest of the columns contain the pixel-values of the associated image.

Each pixel column in the training set has a name like pixelx, where x is an integer between 0 and 783, inclusive. To locate this pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27, inclusive. Then pixelx is located on row i and column j of a 28 x 28 matrix, (indexing by zero).

------------------------
| Run Code              |
------------------------
1. py -m venv venv (if you have windows pc)
   
   a) .\venv\Scripts\activate
   
   b) py -m pip install --upgrade pip
   
   c) pip install jupyter numpy pandas seaborn matplotlib scikit-learn tensorflow
   
   d) jupyter-notebook (For open jupyter)
2. python3 -m venv venv (if you have mac or linux)

   a) source ./venv/bin/activate
   
   b) python3 -m pip install --upgrade pip
   
   c) pip install jupyter numpy pandas seaborn matplotlib scikit-learn tensorflow
   
   d) jupyter-notebook (For open jupyter)
