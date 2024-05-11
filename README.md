# Lecture: Data Analysis
**憊思參差識無常 遍履方圜飛神仙**

<img src="./images/cover.png" alt="Cover" width="800px"/>

* Time: (2023 March 03/07) 2-5 pm
* Lecturer: [Hauyu Baobab Liu](https://baobabyoo.github.io/) (呂浩宇)
* Location: NSYSU, 物理系館二樓演講廳
* Language: 中文

<img src="./images/Lecture_DataAnalysis_2023Feb_QR.png" alt="QRcode" width="200px"/>

## Textbook and References
- [Numerical Recipes, 3rd ed.](http://numerical.recipes/book/book.html)
- [emcee](https://emcee.readthedocs.io/en/stable/) [tutorial](https://emcee.readthedocs.io/en/stable/tutorials/line/)
- Good references for artificial neural network and machine learning
 1. [UA-ASTR502](https://github.com/UA-ASTR502-2022/astr502?fbclid=IwZXh0bgNhZW0CMTAAAR1Q8Wz8_XHHmSFdDVhyFZOYnzF3wBvHlRrBk_MV88Xk5ypqbC_-KU8RHKA_aem_AQmresWOdpAEBcDGZ8QxaOAWpL90SLulatoeZ6prBmbtnCiyc4g2p4pCJzE0qHrH2ts6Qbm-H-zagk0U3hFw4QnP)
 2. [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com)


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
linux> pip install scipy
linux> pip install emcee corner tqdm
linux> pip install h5py
```
If you need an instruction about how to install Anaconda, check [my webpage](https://baobabyoo.github.io/pages/students_topics/software_tips_python.html)

## Syllabus
1. Principle of least square and $\chi$ square fittings
2. Fitting a line
 - principle
 - Python code
3. Non-linear problem (Levenberg-Marquart method)
 - principle
 - Python code (taking 1D Gaussian as an example)
4. Bayesian inference
5. Markov Chain Monte Carlo method
6. Applications of artificial neural network

## Lecture Notes
1. [Part 1: General Concepts and Chi-Square fittings](https://github.com/baobabyoo/Lecture_DataAnalysis/blob/main/lecture_notes/DataAnalysis_part1.pdf)
2. [Part 2: Chi-Squre fittings in linear problem](https://github.com/baobabyoo/Lecture_DataAnalysis/blob/main/lecture_notes/DataAnalysis_part2.pdf)
3. [Part 3: Non-linear Chi-Square minimization and goodness-of-fittings](https://github.com/baobabyoo/Lecture_DataAnalysis/blob/main/lecture_notes/DataAnalysis_part3.pdf)
4. [Part 4: Markov Chain Monte Carlo method](https://github.com/baobabyoo/Lecture_DataAnalysis/blob/main/lecture_notes/DataAnalysis_part4.pdf)

## Example Python Code
- [Jupyter Notebook - Frequentist](https://github.com/baobabyoo/Lecture_DataAnalysis/blob/main/DataAnalysisLecture_2023March_frequentist.ipynb) (Note that the codes are redundant for a pedagogical purpose. Normally we should not make the codes looking like that.)
- [Jupyter Notebook - MCMC](https://github.com/baobabyoo/Lecture_DataAnalysis/blob/main/DataAnalysisLecture_2023March_MCMC.ipynb) (Note that the codes are redundant for a pedagogical purpose. Normally we should not make the codes looking like that.)
