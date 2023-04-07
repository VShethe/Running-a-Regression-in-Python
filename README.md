
# Running a Regression 





## Table of Content


1. Running a Regression for Housing Data

## Project Description

1. **Regression analysis:**
Regression analysis is a statistical technique used to examine the relationship between a dependent variable and one or more independent variables. In the context of finance, regression analysis is often used to analyze the relationship between financial variables such as stock prices, interest rates, and economic indicators.

```bash
# Define the dependent variable and independent variables
y = data['stock_price']
X = data[['interest_rate', 'gdp_growth', 'inflation']]

Ordinary least square estimates(OLS)

# Add a constant term to the independent variables
X = sm.add_constant(X)

Formula for # Fit the linear regression model:
reg = sm.OLS(Y, X1).fit()

reg.summary()

```


## Installation

To install numpy

```bash
pip install numpy
```

To install pandas:

```bash
pip install pandas
```

To install scipy:

```bash
pip install scipy
```

To install matplotlib:

```bash
pip install -U matplotlib
```

## Deployment

To deploy this project run

```bash
import numpy as np
import pandas as pd

from scipy import stats
import statsmodels.api as sm

import matplotlib.pyplot as plt
```



