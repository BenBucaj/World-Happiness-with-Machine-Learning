## pip
This installation uses Python Package Installer (PyPI). 
Usually <b>pip</b> comes installed with Python, but if your local machine does not have <b>pip</b> installed, you may download <b>pip</b> by running the following command on Terminal:
```
sudo apt update
sudo apt install python3-pip
```
To verify the installation, open a terminal/command prompt and type:
```
pip --version
```
If you see a version number, pip is installed correctly
## Installing the required packages
Once <b>pip</b> is installed, download the requirements file located in [../requirements.txt](https://github.com/FilipLe/World-Happiness/tree/main/prerequisites) and run the following command on your Terminal:
```
pip install -r requirements.txt
```
## About the libraries
### NumPy
<h1 align="center">
<img src="https://raw.githubusercontent.com/numpy/numpy/main/branding/logo/primary/numpylogo.svg" width="150">
</h1><br>

[![PyPI Latest Release](https://img.shields.io/pypi/v/numpy.svg)](https://pypi.org/project/numpy/)
[![PyPI Downloads](https://img.shields.io/pypi/dm/numpy.svg?label=PyPI%20downloads)](
https://pypi.org/project/numpy/)
[![Stack Overflow](https://img.shields.io/badge/stackoverflow-Ask%20questions-blue.svg)](
https://stackoverflow.com/questions/tagged/numpy)
[![Package Status](https://img.shields.io/pypi/status/numpy.svg)](https://pypi.org/project/numpy/)
[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](
https://numfocus.org)

#### Description
NumPy adds support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.

For more, check out NumPy's documentation: [https://numpy.org/doc](https://numpy.org/doc)

#### Installation:
Run the following command in your Terminal:
```
pip install numpy
(or)
pip3 install numpy
```


### pandas
<h1 align="center">
<img src="https://pandas.pydata.org/static/img/pandas.svg" width="150">
</h1><br>

[![PyPI Latest Release](https://img.shields.io/pypi/v/pandas.svg)](https://pypi.org/project/pandas/)
[![Downloads](https://img.shields.io/pypi/dm/pandas)](https://pypi.org/project/pandas)
[![Stack Overflow](https://img.shields.io/badge/stackoverflow-Ask%20questions-blue.svg)](
https://stackoverflow.com/questions/tagged/pandas)
[![Package Status](https://img.shields.io/pypi/status/pandas.svg)](https://pypi.org/project/pandas/)
[![License](https://img.shields.io/pypi/l/pandas.svg)](https://github.com/pandas-dev/pandas/blob/main/LICENSE)
[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

#### Description
pandas offers data manipulation and analysis abilities. In particular, it offers data structures and operations for manipulating numerical tables and time series.

For more, check out pandas documentation: [https://pandas.pydata.org/pandas-docs/stable](https://pandas.pydata.org/pandas-docs/stable)

#### Installation:
Run the following command in your Terminal:
```
pip install pandas
(or)
pip3 install pandas
```


### matplotlib
<h1 align="center">
<img src="https://matplotlib.org/_static/logo2.svg" width="150">
</h1><br>

[![PyPi](https://img.shields.io/pypi/v/matplotlib)](https://pypi.org/project/matplotlib/)
[![Downloads](https://img.shields.io/pypi/dm/matplotlib)](https://pypi.org/project/matplotlib)
[![Stack Overflow](https://img.shields.io/badge/stackoverflow-Ask%20questions-blue.svg)](
https://stackoverflow.com/questions/tagged/matplotlib)
[![Discourse help forum](https://img.shields.io/badge/help_forum-discourse-blue.svg)](https://discourse.matplotlib.org)
[![Package Status](https://img.shields.io/pypi/status/matplotlib.svg)](https://pypi.org/project/matplotlib/)
[![NUMFocus](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)


#### Description
Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.

For more, check out Matplotlib's documentation: [https://matplotlib.org/stable/index.html](https://matplotlib.org/stable/index.html)

#### Installation:
Run the following command in your Terminal:
```
pip install matplotlib
(or)
pip3 install matplotlib
```


### seaborn
<h1 align="center"><img src="https://raw.githubusercontent.com/mwaskom/seaborn/master/doc/_static/logo-wide-lightbg.svg" width="150"></h1><br>

[![PyPI Version](https://img.shields.io/pypi/v/seaborn.svg)](https://pypi.org/project/seaborn/)
[![Downloads](https://img.shields.io/pypi/dm/seaborn)](https://pypi.org/project/seaborn)
[![Stack Overflow](https://img.shields.io/badge/stackoverflow-Ask%20questions-blue.svg)](
https://stackoverflow.com/questions/tagged/seaborn)
[![License](https://img.shields.io/pypi/l/seaborn.svg)](https://github.com/mwaskom/seaborn/blob/master/LICENSE)
[![Tests](https://github.com/mwaskom/seaborn/workflows/CI/badge.svg)](https://github.com/mwaskom/seaborn/actions)

#### Description
Seaborn is a statistical data visualization library based on matplotlib. It provides a high-level interface for drawing attractive statistical graphics.

For more, check out seaborn's documentation: [https://seaborn.pydata.org](https://seaborn.pydata.org)
#### Installation:
Run the following command in your Terminal:
```
pip install seaborn
(or)
pip3 install seaborn
```


### scikit-learn
<h1 align="center">
<img src="https://raw.githubusercontent.com/scikit-learn/scikit-learn/main/doc/logos/scikit-learn-logo.png" width="150">
</h1>

[![PyPi](https://img.shields.io/pypi/v/scikit-learn)](https://pypi.org/project/scikit-learn/)
[![PyPI Downloads](https://img.shields.io/pypi/dm/scikit-learn.svg?label=PyPI%20downloads)](
https://pypi.org/project/scikit-learn/)
[![Stack Overflow](https://img.shields.io/badge/stackoverflow-Ask%20questions-blue.svg)](
https://stackoverflow.com/questions/tagged/scikit-learn)
[![Package Status](https://img.shields.io/pypi/status/scikit-learn.svg)](https://pypi.org/project/scikit-learn/)

#### Description
scikit-learn is a machine learning library, which offers various classification, regression and clustering algorithms.

For more, check out scikit-learn's documentation: [https://scikit-learn.org/0.21/documentation.html](https://scikit-learn.org/0.21/documentation.html)

#### Requirements
- Python (>= 3.8)
- NumPy (>= 1.17.3)
- SciPy (>= 1.5.0)
- joblib (>= 1.1.1)
- threadpoolctl (>= 2.0.0)

#### Installation
Run the following command in your Terminal:
```
pip install scikit-learn
(or)
pip3 install scikit-learn
```
