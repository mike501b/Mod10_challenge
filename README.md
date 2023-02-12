# Mod10_challenge

This is a python script that compares the KMeans model using original data vs PCA data
The script uses "cypto_market_data.csv" to compile the data.
---

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For access to Pandas series and dataframes.

* [pathlib](https://github.com/budlight/pathlib) - To load csv files.

* [hvplot.pandas](hvplot.pandas) - To plot data.

* [sklearn](https://scikit-learn.org/stable/) - To use sklearn.cluster KMeans, sklearn.decomposition PCA and sklearn.preprocessing StandardScaler

---

## Installation Guide

Before running the application first install the following dependencies.

```python
import pandas as pd
import hvplot.pandas
from pathlib import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
```

---

## Usage

To use the model analyzer script simply clone the repository and crypto_investments.ipynb

```python
crypto_investments.ipynb
```



---

## Contributors

Mike Blanchette

---

## License

When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.
