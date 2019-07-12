# Case-Study-Boston-Housing-Price-Prediction

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](https://www.numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [Jupyter Notebook](https://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://www.anaconda.com/download/) distribution of Python, which already has most of the above packages and more included or if you don't want to install a huge number of packages then you can try [Miniconda](https://conda.io/miniconda.html) and then install the above packages.

### Code

Code is in the [Boston_Housing_Case_Study.ipynb](Boston_Housing_Case_Study.ipynb) notebook file. Also required  the [boston_housing.csv](boston_housing.csv) dataset file.

### Run

In a terminal or command window, navigate to the top-level project directory `boston_housing/` (that contains this README) and run one of the following commands:

```bash
jupyter notebook boston_housing.ipynb
```

or

```bash
ipython notebook boston_housing.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.


### Data
The dataset used in this project can be found in [boston_housing.csv](boston_housing.csv) dataset file.

**Features**

1. `crim` - per capita crime rate by town.
2. `zn` - proportion of residential land zoned for lots over 25,000 sq.ft.
3. `indus` - proportion of non-retail business acres per town.
4. `chas` - Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).
5. `nox` - nitrogen oxides concentration (parts per 10 million).
6. `rm` - average number of rooms per dwelling.
7. `age` - proportion of owner-occupied units built prior to 1940.
8. `dis` - weighted mean of distances to five Boston employment centres.
9. `rad` - index of accessibility to radial highways.
10. `tax` - full-value property-tax rate per \$10,000.
11. `ptratio` - pupil-teacher ratio by town.
12. `b` - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town.
13. `lstat` - lower status of the population (percent).

**Target Variable**

14. `medv` - median value of owner-occupied homes in \$1000s.

### Project Structure

Whole case study is implemented using machine learning template which contains 6 steps as follows

1. Prepare Problem
`a) Load libraries`
`b) Load dataset`

2. Summarize Data
`a) Descriptive statistics`
`b) Data visualizations`

3. Prepare Data
`a) Data Cleaning`
`b) Feature Selection`
`c) Data Transforms`

4. Evaluate Algorithms
`a) Split-out validation dataset`
`b) Test options and evaluation metric`
`c) Spot Check Algorithms`
`d) Compare Algorithms`

5. Improve Accuracy
`a) Algorithm Tuning`
`b) Ensembles`

6. Finalize Model
`a) Predictions on validation dataset`
`b) Create standalone model on entire training dataset`
`c) Save model for later use`

