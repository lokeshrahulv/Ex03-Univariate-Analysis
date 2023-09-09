# Ex03-Univariate-Analysis
## AIM:
To Perform Univariate Analysis on the given data
## ALGORITHM:
### STEP 1:
Read the given data 
### STEP 2:
Get information from the data 
### Step 3:
Remove the null values from the data.
### Step 4:
Mention the datatypes from the data.
### Step 5:
Count the values from the data.
### Step 6:

Do plots like boxplots,countplot,distribution plot,histogram plot.
## PROGRAM:
```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

df=pd.read_csv("/content/iris (1).csv")

df.nunique()
```


