# This projet is part of the:
# Machine Learning Engineer Nanodegree
# Content: Unsupervised Learning
## Project: Creating Customer Segments

### Goal of the Project
This machine learning project is designed to give hands-on experience with unsupervised learning and work towards developing conclusions for a potential client on a real-world dataset.

### Achievements
- I explored the data by selecting a small subset to sample and determine if any product categories highly correlate with one another. 
- Preprocessed the data by scaling each product category and then identifying (and removing) unwanted outliers.
- Applied PCA transformations to the data and implement clustering algorithms to segment the transformed customer data. 
- Applied unsupervised learning techniques such as K-Means, Gaussian Mixture Model clustering algorithm.
- Identified customer segments (clusters) hidden in the data of product spending data collected for customers of a wholesale distributor in Lisbon, Portugal.


### Install

This project was done using **Python 2.7** that already supports the following Python libraries:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

I installed the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included and I made sure that you select the Python 2.7 installer.



## Data

The customer segments data is included as a selection of 440 data points collected on data found from clients of a wholesale distributor in Lisbon, Portugal. More information can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers).

Note (m.u.) is shorthand for *monetary units*.

**Features**
1) `Fresh`: annual spending (m.u.) on fresh products (Continuous);
2) `Milk`: annual spending (m.u.) on milk products (Continuous);
3) `Grocery`: annual spending (m.u.) on grocery products (Continuous);
4) `Frozen`: annual spending (m.u.) on frozen products (Continuous);
5) `Detergents_Paper`: annual spending (m.u.) on detergents and paper products (Continuous);
6) `Delicatessen`: annual spending (m.u.) on and delicatessen products (Continuous);
7) `Channel`: {Hotel/Restaurant/Cafe - 1, Retail - 2} (Nominal)
8) `Region`: {Lisbon - 1, Oporto - 2, or Other - 3} (Nominal)
