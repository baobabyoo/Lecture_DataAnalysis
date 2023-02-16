# Lecture: Data Analysis
* Time: (2023 March 03/07) 2-5 pm
* Lecturer: [Hauyu Baobab Liu](https://baobabyoo.github.io/) (呂浩宇)
* Location: NSYSU, 物理系館二樓演講廳
* Language: 中文

<img src="./images/Lecture_DataAnalysis_2023Feb_QR.png" alt="QRcode" width="200px"/>

## Purpose
Comparing *data* with a *model* that depends on adjustable parameters, with the aid of the figure-of-merit function (**merit function** for short):
- finding the best-fit parameters.
- knowing the standard errors of the parameters
- assessing goodness-of-fit

## Approaches
- [Frequentist inference](https://en.wikipedia.org/wiki/Frequentist_inference)
- [Bayesian inference](https://en.wikipedia.org/wiki/Bayesian_inference)

## Constructing the [Anaconda](https://www.anaconda.com/products/distribution) [Python](https://www.python.org/) Environment
(this installed Python 3.10.9; also working on Macbook)
```
# 2023.Feb.16
# jupyter is our programing interface
# numpy is an useful package to deal with numerical methods
# matplotlib is our plotting package
# pandas is the package to deal with file I/O
# emcee and corner are the packages to do MCMC
# tqdm is the package to allow show progress bars when running  a python code 
linux> conda create --name dataanalysis_lecture pip
linux> conda activate dataanalysis_lecture
linux> pip install --upgrade pip
linux> pip install jupyter numpy matplotlib pandas
linux> pip install emcee corner tqdm
```
