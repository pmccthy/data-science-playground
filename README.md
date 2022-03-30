# Data Science Playground

This repo is a place where I play around with machine learning models and digital signal processing algorithms to get an understanding of how they work and how to implement them with standard libraries. This includes classic statistical models, probabilistic models, deep learning, and DSP concepts and algorithms. As this grows, I may refactor it out into two repos to separate the ML and DSP content, but for now it is intermixed. This repo focuses on practical implementation rather than fleshing out the mathematical details of the ML techniques used here. For learning ML theory, I have used the textbook _Pattern Recognition and Machine Learning_ by Christopher Bishop, a free copy of which can be found [here](http://users.isr.ist.utl.pt/~wurmd/Livros/school/Bishop%20-%20Pattern%20Recognition%20And%20Machine%20Learning%20-%20Springer%20%202006.pdf). The Bishop book focuses on understand ML from the foundations of probability theory and statistics, but doesn't include much deep learning. A good textbook for deep learning theory is _Deep Learning_ by Ian Goodfellow, Yoshua Bengio and Aaron Courville, an online version of which can be found [here](https://www.deeplearningbook.org/). Notebooks are generally organised by model type (e.g. autoencoders) rather than by application (e.g. dimensionality reduction), which means that models that are associated or used for the same purpose may be located under different subdirectories/ headings.

**DISCLAIMER**: This repo exists for my own benefit; its constituent Notebooks are not written in a tutorial-style format and some of them may be very rough or even unfinished. Therefore, this repo may not be much use to those wishing to learn to *understand* the relevant content themselves, though they may contain links to online tutorials which could help with this.

## Convolutional Neural Networks (CNNs)

* [CNNs/vanilla_cnn.ipynb](CNNs/vanilla_cnn.ipynb): Generic CNN architectures

## Recurrent Neural Networks (RNNs)

* [RNNs/vanilla_rnn.ipynb](RNNs/vanilla_rnn.ipynb): Generic RNN architectures
* [RNNs/lstm.ipynb](RNNs/lstm.ipynb): RNNs which use Long Short-Term Memory (LSTM) blocks

## Autoencoders

* [autoencoders/vanilla_autoencoder.ipynb](autoencoders/vanilla_autoencoder.ipynb): Generic autoencoder architecture

## Decompositions

* [decompositions/svd.ipynb](decompositions/svd.ipynb): Singular value decomposition exploration
* [decompositions/pca.ipynb](decompositions/pca.ipynb): Principal component analysis exploration

## Classical Classification Models

* [classification/lda.ipynb](classification/lda.ipynb): Linear discriminant analysis exploration

## Transforms

* [transforms/fft_from_scratch.ipynb](transforms/fft_from_scratch.ipynb): Implementation of the FFT algorithm from scratch to compute the DFT
* [transforms/hilbert.ipynb](transforms/hilbert.ipynb): Explores the Hilbert transform and its use for computing instantaneous phase and frequency

## Windows

* [windows.ipynb](windows.ipynb): Explores the uses of different window functions in the time and frequency domains

## ML categories to explore

* Transformers
* Graph Neural Networks (GNNs)
* GANs (StyleGAN, CycleGAN etc.)
* Probabilistic Graphical Models (HMRFs, Bayesian Networks etc.)
* Classical Regression Models (GLMs etc.)
* Classical Classification Models (LDA, KNN, Naive-Bayes etc.)
* Classical Clustering Models (K-means, hierarchical etc.)
* Kernel-based methods (SVMs etc.)
* Maximum-Likelihood Estimation

## DSP areas to explore

* Time series modelling (ARMA)
* Transforms (FFT, Laplace, Wavelet, Hilbert etc.)
* Decompositions (SVD, PCA, NMF, EMD etc.)
* Windows (comparison of different pre-FFT windows in time and frequency domains)

## ML areas to do comparitive studies on

* Optimisation algorithms
* Regularisation
* Loss functions
* One-shot learning
