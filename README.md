# Ex03-Univariate-Analysis
Aim
To read the given data and perform the univariate analysis with different types of plots.

Explanation
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.

Algorithm
Step1:
Read the given data.

Step2:
Get the information about the data.

Step3:
Remove the null values from the data.

Step4:
Mention the datatypes from the data.

Step5:
Count the values from the data.

Step6:
Do plots like boxplots,countplot,distribution plot,histogram plot.

Program
For SuperStore.csv:
Developed by : vidhyasri.k
Registration Number : 212222230170

import pandas as pd
import numpy as np
import seaborn as sns
df=pd.read_csv("SuperStore.csv")
df
df.head()

df.info()

df.describe()

df.isnull().sum()

df.dtypes

df['Sales'].value_counts()

sns.boxplot(x="Sales", data=df)

sns.countplot(x="Sales", data=df)

sns.distplot(df["Sales"])

sns.histplot(x="Sales", data=df)

For diabetes.csv

Developed by : vidhyasri.k
Registration Number : 212222230170

import pandas as pd

import numpy as np

import seaborn as sns

df=pd.read_csv("diabetes.csv.csv")

df

df.head()

df.info()

df.describe()

df.isnull().sum()

df.dtypes

df['Age'].value_counts()

sns.boxplot(x="Age", data=df)

sns.countplot(x="Age", data=df)

sns.distplot(df["Age"])

sns.histplot(x="Age", data=df)

OUTPUT

FOR SuperStore.csv:
DATA
![image](https://github.com/vidhyasrikachapalayam/Ex03-Univariate-Analysis/assets/119477817/b3b42f57-5b32-4fc0-bdc0-218a5f8096a3)


DATA HEAD

![image](https://github.com/vidhyasrikachapalayam/Ex03-Univariate-Analysis/assets/119477817/b094844c-d59b-4813-81d5-730ce459d833)


DATA INFORMATION

![image](https://github.com/vidhyasrikachapalayam/Ex03-Univariate-Analysis/assets/119477817/bf30b1fc-585d-4aa9-8278-56edb2d853a2)



DATA DESCRIBE

![image](https://github.com/vidhyasrikachapalayam/Ex03-Univariate-Analysis/assets/119477817/508369bc-a5a4-4a45-94f9-6624c49aeef2)


DATA NULL VALUES

![image](https://github.com/vidhyasrikachapalayam/Ex03-Univariate-Analysis/assets/119477817/4d495bc5-ee9f-472c-8b16-53de2611a256)


DATA DATA TYPES

![image](https://github.com/vidhyasrikachapalayam/Ex03-Univariate-Analysis/assets/119477817/e3c9ab67-f259-4abe-a68f-110086668531)

DATA VALUE COUNT

![image](https://github.com/vidhyasrikachapalayam/Ex03-Univariate-Analysis/assets/119477817/0ea3c791-dca1-4a27-ac0b-062550e46c9c)

BOX PLOT

![image](https://github.com/vidhyasrikachapalayam/Ex03-Univariate-Analysis/assets/119477817/ae90fd9b-d763-46f4-b7ec-a473a0cbdb0c)

COUNT PLOT

![image](https://github.com/vidhyasrikachapalayam/Ex03-Univariate-Analysis/assets/119477817/5a5a99fe-a2c2-48df-8cbe-6eee54b08a25)

DISTRIBUTION PLOT

![image](https://github.com/vidhyasrikachapalayam/Ex03-Univariate-Analysis/assets/119477817/ccafac7d-b834-4c7b-9ed2-9786bdda571a)

HISTOGRAM PLOT

![image](https://github.com/vidhyasrikachapalayam/Ex03-Univariate-Analysis/assets/119477817/4e2722de-f2c3-40bf-8ee8-fd61ff74562c)

RESULT

Thus we have read the given data and performed the univariate analysis with different types of plots.
