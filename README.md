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
Developed by : SUJITHRA B K N
Registration Number : 212222230153

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
Developed by : SUJITHRA B K N
Registration Number : 212222230153

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
Screenshot 2023-03-29 193120

DATA HEAD
Screenshot 2023-03-29 193142

DATA INFORMATION
Screenshot 2023-03-29 193155

DATA DESCRIBE
Screenshot 2023-03-29 193203

DATA NULL VALUES
Screenshot 2023-03-29 193211

DATA DATA TYPES
Screenshot 2023-03-29 193218

DATA VALUE COUNT
Screenshot 2023-03-29 193227

BOXPLOT
