# Bertelsmann Arvato customers IA

### Table of Contents

1. [Overview](#overview)
2. [Installation](#installation)
3. [Running](#running)
4. [Repository Structure](#repo)
5. [Final Considerations](#considerations)

## Overview <a name="overview"></a>

The goal of this project is to create a Customer Segmentation Report for 
Arvato Financial Solutions.
At this project, you will find a notebook showing the exploratory data analysis,
the data wrangling and the unsupervised learning algorithm and a folder with 
multiple notebooks each one with a technique to try to get the best supervised
learning model.

This project is part of the Udacity Data Science Nanodegree program.

## Installation <a name="installation"></a>

Create a virtual environment named **customers_seg**.

```
$ python3 -m venv customers_seg -- for Linux and macOS
$ python -m venv customers_seg -- for Windows
```

After that, activate the Python virtual environment

```
$ source customers_seg/bin/activate -- for Linux and macOS
$ customers_seg\Scripts\activate -- for Windows
```

Install the requirements (The list of requirements may be bigger than the
libraries needed because I got the libraries from the Udacity workspace)

```
$ pip install -r requirements.txt
```

## Running <a name="running"></a>

Unfortunately the data is private and is only available at Udacity workspace.
But just to give you a taste of the data that if you enroll in the nanodegree
you will have access:
* Udacity_AZDIAS_052018.csv: 
    * Demographics data for the general population of Germany; 
    * 891 211 persons (rows) x 366 features (columns).
* Udacity_CUSTOMERS_052018.csv:
    * Demographics data for customers of a mail-order company;
    * 191 652 persons (rows) x 369 features (columns).
* Udacity_MAILOUT_052018_TRAIN.csv: 
    * Demographics data for individuals who were targets of a marketing campaign; 
    * 42 982 persons (rows) x 367 (columns).
* Udacity_MAILOUT_052018_TEST.csv: 
    * Demographics data for individuals who were targets of a marketing campaign; 
    * 42 833 persons (rows) x 366 (columns).

## Repository Structure <a name="repo"></a>

- The `requirements.txt` has the needed packages to run the code.
- `Arvato Project Workbook.ipynb` notebook with the exploratory data analysis,
the data wrangling and the unsupervised learning algorithm
- `terms_and_conditions` The terms and conditions to use the Bertelsmann/Arvato
data
- `supervised_learning_notebooks` folder with all the notebooks used for the
supervised learn part

## Final Considerations and acknowledgments <a name="considerations"></a>
To acomplish those result, I've read many tutorials, articles and documentation 
from https://machinelearningmastery.com, https://www.kaggle.com and of 
course from https://stackoverflow.com to get insights.

Thanks to Bertelsmann/Arvato for kindly make the data of a real problem 
available at Udacity and for all Udacity professors and mentors.
