# Deep_learning_path

Deep learning projects have a lot of code behind them. I believe that the best way of becoming a better programmer is to write every line of code. This is why I've written the code for all these notebooks from scratch.

### Technologies used:

- Python, numpy
- Pytorch, Tensorflow
- Neural Networks
- Convolutional Neural Networks (CNN)
- Recurrent Neural Networks (RNN)
- Long Short Term Memory Neural Networks (LSTM)
- Generative Adversarial Networks (GANs), DVGANs, CycleGANs
- Word embeddings

### Neural Networks

* [Predicting Student Admissions](https://github.com/HannaLAguilar/Deep_Learning_Udacity/blob/master/Deep_learning%20path/Neural%20networks/Predicting%20Student%20Admissions%20with%20Neural%20Networks.ipynb)
* [FMNIST with Pytorch](https://github.com/HannaLAguilar/Deep_Learning_Udacity/blob/master/Deep_learning%20path/Neural%20networks/FMNIST%20with%20Pytorch.ipynb)

### Convolutional Neural Networks (CNN)

* [MNIST](https://github.com/HannaLAguilar/Deep_Learning_Udacity/blob/master/Deep_learning%20path/CNN/MNIST%20CNN.ipynb)
* [FMNIST](https://github.com/HannaLAguilar/Deep_Learning_Udacity/blob/master/Deep_learning%20path/CNN/FMNIST%20CNN.ipynb)
* [cifar10](https://github.com/HannaLAguilar/Deep_Learning_Udacity/blob/master/Deep_learning%20path/CNN/cifar10%20CNN%20.ipynb)
* [Autoencoder](https://github.com/HannaLAguilar/Deep_Learning_Udacity/blob/master/Deep_learning%20path/CNN/Simple%20Autoencoders.ipynb)
* [Autoencoder CNN](https://github.com/HannaLAguilar/Deep_Learning_Udacity/blob/master/Deep_learning%20path/CNN/Autoencoders%20CNN.ipynb)
* [Flowers classifier](https://github.com/HannaLAguilar/Deep_Learning_Udacity/blob/master/Deep_learning%20path/CNN/Flowers%20classifier.ipynb)

### Recurrent Neural Networks (RNN)

* [Simple RNN](https://github.com/HannaLAguilar/Deep_Learning_Udacity/blob/master/Deep_learning%20path/RNN/Simple%20RNN.ipynb)
* [Character prediction LSTM (Anna Karenina)](https://github.com/HannaLAguilar/Deep_Learning_Udacity/blob/master/Deep_learning%20path/RNN/Character%20prediction%20LSTM.ipynb)
* [Sentiment Analysis with RNN](https://github.com/HannaLAguilar/Sentiment_analysis_rnn)

### Word embedding

* [Words embedding: skip gram](https://github.com/HannaLAguilar/Deep_Learning_Udacity/blob/master/Deep_learning%20path/WordEmbeddings/Word2Vec_SkipGram.ipynb)
* [Negative sampling](https://github.com/HannaLAguilar/Deep_Learning_Udacity/blob/master/Deep_learning%20path/WordEmbeddings/Word2Vec_SkipGram_NegativeSampling.ipynb)

### Generative Adversarial Networks (GANs)

* [MNIST GANs](https://github.com/HannaLAguilar/Deep_Learning_Udacity/blob/master/Deep_learning%20path/GANs/MNIST%20GANs.ipynb)
* [DCGANs](https://github.com/HannaLAguilar/Deep_Learning_Udacity/blob/master/Deep_learning%20path/GANs/DeepConvGANs.ipynb)

## Installation

Using [Anaconda](https://www.anaconda.com/products/individual), run the following lines of code:

1. Create an enviroment:
```
conda create -n deep_learning python=3.6
conda activate deep_learning
```

2. Install pytorch and torchvision:
```
conda install -c pytorch pytorch
conda install -c pytorch torchvision
```

3. Install a few required packages, which are specified in the requirements text file (including OpenCV):
```
conda install --file requirements.txt
or
pip install -r requirements.txt
```
