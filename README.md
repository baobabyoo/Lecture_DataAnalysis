# Lecture: Data Analysis
**憊思參差識無常 遍履方圜飛神仙**

* Time: (2023 March 03/07) 2-5 pm
* Lecturer: [Hauyu Baobab Liu](https://baobabyoo.github.io/) (呂浩宇)
* Location: NSYSU, 物理系館二樓演講廳
* Language: 中文

<img src="./images/Lecture_DataAnalysis_2023Feb_QR.png" alt="QRcode" width="200px"/>

## Textbook and References
- [Numerical Recipes, 3rd ed.](http://numerical.recipes/book/book.html)
- [emcee](https://emcee.readthedocs.io/en/stable/) [tutorial](https://emcee.readthedocs.io/en/stable/tutorials/line/)

## Purpose
Comparing *data* with a *model* that depends on adjustable parameters, with the aid of the figure-of-merit function (評價函數; **merit function** for short):
- finding the best-fit parameters (最適參數).
- knowing the standard errors (標準誤差) of the parameters
- assessing goodness-of-fit (適合度)

## Approaches
- [Frequentist inference](https://en.wikipedia.org/wiki/Frequentist_inference) 頻率學派推斷
- [Bayesian inference](https://en.wikipedia.org/wiki/Bayesian_inference) 貝葉斯推斷

## Constructing the [Anaconda](https://www.anaconda.com/products/distribution)  [Python](https://www.python.org/) Environment
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

## Syllabus

1. Principle of $\chi$ square fitting
2.
