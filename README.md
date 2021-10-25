# 🏘️ STUDY PROJECT REPORT : LAND VALUES 2019-2020

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](http://forthebadge.com)

## Overview

**Subject** : Analyse the property values requests of 2019-2020. This project is about using and understanding DataScience and DataVisualisation tools, in particular : pandas with multiple data sources & various visualization modules in particular plotly.

*NOTES: The notebook is in French but do not hesitate to contact me if you want more details in English. Pull requests are welcome ! For major changes, please open an issue first to discuss what you would like to change.*

## 📚🔎 Libraries and Preprocessing

To download the dataset, click on this [link](https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres/).

For this project we will mainly use the following libraries :
```python
# Essential libraries
import json
import random
from urllib.request import urlopen

# Storing and anaysis
import numpy as np
import pandas as pd
import random 
import math

# Visualization
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
import plotly.graph_objs as go
import plotly.figure_factory as ff
import calmap
import folium
```
Use the package manager [pip](https://pip.pypa.io/en/stable/) if you don't have them yet.

In the preprocessing part of our notebook, we transform the raw data into a valuable dataset easier to plot and use for interpretations. We notably get rid of NaN values, inconsistencies, or redundancy using simple Python functions. We only want to keep the data we can extract relevant facts from. We also create new columns such as 'Type voie - code Rivoli' which we will take a look at after.

## 📝 Authors

* **Héloïse DE CASTELNAU** _alias_ [@heloise-de-castelnau](https://github.com/heloise-de-castelnau)
* **Ugo DEMY** _alias_ [@Nibleash](https://github.com/Nibleash) 
