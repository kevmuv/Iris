# Iris
Python code used to visualize data from the Iris dataset from kagel
## Visualizing The Irish Dataset
* In this project we sought to use the Iris dataset in an effort to visualize the data from the different variables into 
a comprehensive format. 
First we imported matplotlib a plotting library, and used the 'inline' backend so that our matplotlib graphs
were included in our notebook next to our code.
* Then we imported pandas, a data processing and CSV file I/O library".Because there are built-in methods in python which overlap
with the pandas methods,we import pandas as pd to avoid the confusion. Pd prefix calls the pandas methods.
*We also imported seaborn, a Python graphing library, but due to the current version of seaborn which generates
multiple warnings. we wrote a code to ignore those warnings. We wrote:
```
import warnings
warnings.filterwarnings("ignore")
```
* Next, we loaded the Iris flower dataset from our desktop, which is in the "../C:\Users\HP\Documents/" directory, and
named it "Iris.csv".
* With the iris dataset now a Pandas DataFrame, we wrote the following code in the jupiter notebook to 
see what's in the iris data.
```
iris = pd.read_csv("Iris.csv") 
iris.head()
```

|id| SepalLenghtCm| SepalWidthCm| PetalLengthCm|PetalWidthCm|Species      |
|--|--------------|-------------|--------------|------------|-------------|
|1|5.1            |3.5          |    1.4       |   0.2      | Iris-setosa |
|2|    4.9        | 3.0         |    1.4       |   0.2      | Iris-setosa |
|3|  4.7          |   3.2       |    1.3       |   0.2      | Iris-setosa |
|4|   4.6         |   3.1       |    1.5       |   0.2      | Iris-setosa |
|5|   5.0         |    3.6      |    1.4       |   0.2      | Iris-setosa |

## Visualition

* we used multiple graphs to showcase data interaction between the different variables. These are scatter, box, violin, and pairplot,
and Andrews curves.

Below are the outcomes:

1. Scatter plot:

<a-entity graph="csv: Iris.csv; id: 1"></a-entity>
