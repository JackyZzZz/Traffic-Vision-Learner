# Traffic Vision Learner
## Description
As research continues in the development of self-driving cars, one of the key challenges is [computer
vision](https://en.wikipedia.org/wiki/Computer_vision), allowing these cars to develop an understanding of their environment from digital images. In particular, this involves the ability to recognize and distinguish road signs – stop signs, speed limit signs, yield signs, and more. 

In this project, we will use [TensorFlow](https://www.tensorflow.org/) to build a neural network to classify road signs based on an image of those signs. To do so, we’ll need a labeled dataset: a collection of images that have already been categorized by the road sign represented in them. 

Several such data sets exist, but for this project, we’ll use the [German Traffic Sign Recognition Benchmark](http://benchmark.ini.rub.de/?section=gtsrb&subsection=news) (GTSRB) dataset, which contains thousands of images of 43 different kinds of road signs.

### Technology
Project is built with:
- Python version: 3.9.12
- pipenv version: 2022.7.4

### Clone the Project
```
git clone https://github.com/JackyZzZz/traffic.git
cd traffic
```

### Dataset
Download the [data set](https://cdn.cs50.net/ai/2020/spring/projects/5/gtsrb.zip) for this project and unzip it. Move the resulting __gtsrb__ directory inside of your **traffic** directory.

### Install dependencies
```
pip3 install -r requirements.txt
```

### Running
Simply run this command.
```
python traffic.py /full/path/to/dataset/
```

## Sources
This software is inspired by and developed on the existed prompt by [Harvard CSCI E-80](https://cs50.harvard.edu/extension/ai/2023/fall/projects/5/traffic/)
