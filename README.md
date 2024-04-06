# Assignment 5

The Assignment 5 deals with creating a repository file with adding a python file used from the previous assignment and explaining the python file on a readme.md in detail.

## Getting Started

We created a Repository at Github by the name Data1202. Where the repository is a public repository with a README.MD. After creating the repository we added a python file which reads "Salaries.csv" file. 

### Loading Library

We installed pandas library in the python file.

```
Import pandas as pd
```

### Load Dataset

After loading the pandas library we loaded the dataset i.e. "Salaries.csv". The dataset includes the Salaries. 

By using the following command

```
dataset = pd.read_csv('C:\\Users\\geetg\\Downloads\\Salaries.csv')
dataset.head()
```

Using describe code for the statistical analysis of the dataset.

```
dataset.describe()
```

Using the above code we get statistical analysis of the dataset which includes information like count, mean, std(standard deviation), max, min, etc.

## Authors

* **Geet Apoorva Gohil**


