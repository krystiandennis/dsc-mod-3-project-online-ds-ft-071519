# Northwind Database

In this project the Northwind database was used to use statistical analysis and hypothesis testing to answer questions that are relevant to the business and its objectives. The Northwind Database was developed by Microsoft. A copy of the schema is located in the Jupyter Notebook.

<img src='Northwind_ERD_updated.png' height=100% width=100%>

## Files

- README.md: Instruction guide
- Module 3 Final Project.ipynb : a jupyter notebook file
- Northwind_small.sqlite : a reduced version of Northwind database
- Northwind_ERD_updated : an image file that includes the schema for the database
- Northwind Traders-Krystian Dennis.pdf: presentation slides that hightlight the results from this project

## Requirements

In order to the code in the jupyter notebook, you must have Python installed on you computer. Use Anaconda, as it had many useful libraries pre-installed. 

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install researchpy.

```bash
!pip install researchpy
```
Import the following libraries:

```python
import sqlite3 
import pandas as pd
import numpy as np
from scipy import stats
from scipy.stats import t
from statistics import mean, stdev
from statsmodels.formula.api import ols
import statsmodels.api as sm
from statsmodels.stats.multicomp import pairwise_tukeyhsd
from statsmodels.stats.multicomp import MultiComparison
from statsmodels.stats.power import TTestIndPower, TTestPower
import researchpy as rp
import matplotlib.pyplot as plt
%matplotlib inline
import seaborn as sns
import warnings
warnings.filterwarnings("ignore")
```
