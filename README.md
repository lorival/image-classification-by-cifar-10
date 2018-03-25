[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

[<img src="https://avatars1.githubusercontent.com/u/36938641?s=200&u=b2d470fe66acc157d8ca8cb3fb815dee47d4466d&v=4" align="right" />](https://github.com/machine-learning-experiments)

# Image classification by CIFAR 10

This project makes image classification using convolutional networks.

> See the [jupyter notebook](https://github.com/machine-learning-experiments/image-classification-by-cifar-10/blob/master/dlnd_image_classification.ipynb)

### Motivation

Understand convolutional networks.

### Built With

- [Python 3](https://www.python.org/download/releases/3.0/) - Language
- [Anaconda](https://www.anaconda.com/what-is-anaconda/) - Python Data Science Platform 
- [Jupyter notebook](http://jupyter.org/) - Web application that allows to create documents that contain live code

### Dataset

[CIFAR 10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset.

## Getting Started

### Prerequisites
1. Download and install [Anaconda](https://www.anaconda.com/download/)
2. Update Anaconda
> ``` 
> $ conda upgrade conda 
> $ conda upgrade --all 
> ```

### Install

1. Clone and enter into the project's root directory by command line
> ``` 
> $ git clone https://github.com/machine-learning-experiments/image-classification-by-cifar-10.git
> ```
2. Create and activate enviroment
> ``` 
> $ conda env create -f enviroment.yaml 
> $ conda activate image-classification-by-cifar-10 
> ```
or
> ``` 
> conda create --name image-classification-by-cifar-10 python=3
> conda activate image-classification-by-cifar-10
> conda install numpy jupyter notebook tqdm tensorflow matplotlib scikit-learn
> ```
3. Start jupyter notebook
> ``` 
> $ jupyter notebook 
> ```
4. Your browser will open showing a list of files, click on the  [dlnd_image_classification.ipynb](https://github.com/machine-learning-experiments/image-classification-by-cifar-10/blob/master/dlnd_image_classification.ipynb) notebook file

## Author

[Lorival Smolski Chapuis](https://github.com/lorival)