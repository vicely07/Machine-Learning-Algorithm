# Machine Learning Algorithm 

## Machine Learning Map

![Machine Learning Map]()

The purpose of this repository is _not_ to implement machine learning algorithms by using 3<sup>rd</sup> party library one-liners _but_ rather to practice implementing these algorithms from scratch and get better understanding of the mathematics behind each algorithm. That's why all algorithms implementations are called "homemade" and not intended to be used for production.

## Supervised Learning

In supervised learning we have a set of training data as an input and a set of labels or "correct answers" for each training set as an output. Then we're training our model (machine learning algorithm parameters) to map the input to the output correctly (to do correct prediction). The ultimate purpose is to find such model parameters that will successfully continue correct _input→output_ mapping (predictions) even for new input examples.

### Regression

In regression problems we do real value predictions. Basically we try to draw a line/plane/n-dimensional plane along the training examples.

_Usage examples: stock price forecast, sales analysis, dependency of any number, etc._

#### 🤖 Linear Regression

- 📗 [Math | Linear Regression](homemade/linear_regression) - theory and links for further readings
- ⚙️ [Code | Linear Regression](homemade/linear_regression/linear_regression.py) - implementation example
- ▶️ [Demo | Univariate Linear Regression](https://nbviewer.jupyter.org/github/trekhleb/homemade-machine-learning/blob/master/notebooks/linear_regression/univariate_linear_regression_demo.ipynb) - predict `country happiness` score by `economy GDP`
- ▶️ [Demo | Multivariate Linear Regression](https://nbviewer.jupyter.org/github/trekhleb/homemade-machine-learning/blob/master/notebooks/linear_regression/multivariate_linear_regression_demo.ipynb) - predict `country happiness` score by `economy GDP` and `freedom index`
- ▶️ [Demo | Non-linear Regression](https://nbviewer.jupyter.org/github/trekhleb/homemade-machine-learning/blob/master/notebooks/linear_regression/non_linear_regression_demo.ipynb) - use linear regression with _polynomial_ and _sinusoid_ features to predict non-linear dependencies

### Classification

In classification problems we split input examples by certain characteristic.

_Usage examples: spam-filters, language detection, finding similar documents, handwritten letters recognition, etc._

#### 🤖 Logistic Regression

- 📗 [Math | Logistic Regression](homemade/logistic_regression) - theory and links for further readings
- ⚙️ [Code | Logistic Regression](homemade/logistic_regression/logistic_regression.py) - implementation example
- ▶️ [Demo | Logistic Regression (Linear Boundary)](https://nbviewer.jupyter.org/github/trekhleb/homemade-machine-learning/blob/master/notebooks/logistic_regression/logistic_regression_with_linear_boundary_demo.ipynb) - predict Iris flower `class` based on `petal_length` and `petal_width`
- ▶️ [Demo | Logistic Regression (Non-Linear Boundary)](https://nbviewer.jupyter.org/github/trekhleb/homemade-machine-learning/blob/master/notebooks/logistic_regression/logistic_regression_with_non_linear_boundary_demo.ipynb) - predict microchip `validity` based on `param_1` and `param_2`
- ▶️ [Demo | Multivariate Logistic Regression | MNIST](https://nbviewer.jupyter.org/github/trekhleb/homemade-machine-learning/blob/master/notebooks/logistic_regression/multivariate_logistic_regression_demo.ipynb) - recognize handwritten digits from `28x28` pixel images
- ▶️ [Demo | Multivariate Logistic Regression | Fashion MNIST](https://nbviewer.jupyter.org/github/trekhleb/homemade-machine-learning/blob/master/notebooks/logistic_regression/multivariate_logistic_regression_fashion_demo.ipynb) - recognize clothes types from `28x28` pixel images

## Unsupervised Learning

Unsupervised learning is a branch of machine learning that learns from test data that has not been labeled, classified or categorized. Instead of responding to feedback, unsupervised learning identifies commonalities in the data and reacts based on the presence or absence of such commonalities in each new piece of data.

### Clustering

In clustering problems we split the training examples by unknown characteristics. The algorithm itself decides what characteristic to use for splitting.

_Usage examples: market segmentation, social networks analysis, organize computing clusters, astronomical data analysis, image compression, etc._

#### 🤖 K-means Algorithm

- 📗 [Math | K-means Algorithm](homemade/k_means) - theory and links for further readings
- ⚙️ [Code | K-means Algorithm](homemade/k_means/k_means.py) - implementation example
- ▶️ [Demo | K-means Algorithm](https://nbviewer.jupyter.org/github/trekhleb/homemade-machine-learning/blob/master/notebooks/k_means/k_means_demo.ipynb) - split Iris flowers into clusters based on `petal_length` and `petal_width`

### Anomaly Detection

Anomaly detection (also outlier detection) is the identification of rare items, events or observations which raise suspicions by differing significantly from the majority of the data.

_Usage examples: intrusion detection, fraud detection, system health monitoring, removing anomalous data from the dataset etc._

#### 🤖 Anomaly Detection using Gaussian Distribution

- 📗 [Math | Anomaly Detection using Gaussian Distribution](homemade/anomaly_detection) - theory and links for further readings
- ⚙️ [Code | Anomaly Detection using Gaussian Distribution](homemade/anomaly_detection/gaussian_anomaly_detection.py) - implementation example
- ▶️ [Demo | Anomaly Detection](https://nbviewer.jupyter.org/github/trekhleb/homemade-machine-learning/blob/master/notebooks/anomaly_detection/anomaly_detection_gaussian_demo.ipynb) - find anomalies in server operational parameters like `latency` and `threshold`

## Neural Network (NN)

The neural network itself isn't an algorithm, but rather a framework for many different machine learning algorithms to work together and process complex data inputs.

_Usage examples: as a substitute of all other algorithms in general, image recognition, voice recognition, image processing (applying specific style), language translation, etc._

#### 🤖 Multilayer Perceptron (MLP)

- 📗 [Math | Multilayer Perceptron](homemade/neural_network) - theory and links for further readings
- ⚙️ [Code | Multilayer Perceptron](homemade/neural_network/multilayer_perceptron.py) - implementation example
- ▶️ [Demo | Multilayer Perceptron | MNIST](https://nbviewer.jupyter.org/github/trekhleb/homemade-machine-learning/blob/master/notebooks/neural_network/multilayer_perceptron_demo.ipynb) - recognize handwritten digits from `28x28` pixel images
- ▶️ [Demo | Multilayer Perceptron | Fashion MNIST](https://nbviewer.jupyter.org/github/trekhleb/homemade-machine-learning/blob/master/notebooks/neural_network/multilayer_perceptron_fashion_demo.ipynb) - recognize the type of clothes from `28x28` pixel images

