# MI@O Software Download Guide
Max Kramer, Oberlin College 2020

This document serves as a guide to take a standard laptop and configure Python and packages to facilitate programming for Machine Learning.

I will describe:
- Python versions
- Dependencies
---
# Python Versions

`Note: Python 3.7 and Tensorflow are currently incompatible`

The recommended version of Python to install is 3.6.8, the final version of Python 3.6
it can be found **[here](https://www.python.org/downloads/release/python-368/)**

When installing Python, please remember to select `add Python to PATH` on Windows. This allows for adding Python to the environment variables, which assists anything that needs to find a path back to Python in order to run.

With Python, IDLE, and pip installed on your computer, you are ready to start installing the packages that most Machine Learning in Python uses as dependencies.

---
# Installing Dependencies

There are several packages for data science and modeling available in Python, but most ML developers rely on a small bank of useful programs. They can be installed using the following commands in your terminal.

```sh
$ pip3 install --upgrade tensorflow
$ pip3 install pandas
$ pip3 install scikit-learn
$ pip3 install matplotlib
```

All of these packages have different functions, which are discussed below along with example code for each.

---
# Tensorflow - Neural Network Implementation
Tensorflow is the primary package for developing neural network models in Pytho. Developed by Google, Tensorflow (tf) contains functions that make it much easier to implement different NN models, such as loss and optimizer functions as well as summary statistics reporting.

# Numpy - Mathematics
The numpy library contains functions that facilitate easy mathematical computation in Python.

# Matplotlib.pyplot - Data Visualization
matplotlib


# Pandas - Data Wrangling
The pandas library is the go-to library for reading data from external files into Python. Many common data file formats (CSV, Excel, SQL) can be easily morphed into dataframes reminiscent of R or MATLAB data input.

Overview of basic commands:
- Data Input
    - pd.read_filetype()
        - opens a file of a given format 
    - df.to_filyetype()
        - saves the current dataframe *df* to a supplied filetype (CSV,XLSX)
    - pd.DataFrame()
        - converts Python objects (lists, dictionaries) into dataframes
- Data Visualization
    - df.shape
        - returns a tuple of the x,y dimensions of the dataframe
    - df.head(n)
        - returns the first n rows of the dataframe
    - df.tail(n)
        - returns the last n rows of the dataframe
    - df.info()
        - returns index, datatype, and memory information
- Summary Statistics
    - df.describe()
        - returns summary statistics on each column
    - df.corr()
        - returns correlation between all columns in a dataframe
    -  df.mean()
    - df.median()
    - df.std()
    - df.max()
    - df.min()
- Selection
    - f

     




# Scikit-learn - ML Algorithm Implementations
