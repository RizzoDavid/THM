# O Data, All Ye Faithful

This day will involve data science and its application in cybersecurity, a python introduction, and a general understanding of networks. 

## Background Knowlege

### Data Science 101

Data science is basically interpreting data to answer questions. It can often involve programming. statistics, and artificial intelligence (AI) to analyze large sets of data for trends and patterns to help make predictions.

#### How can data science be used in cybersecurity?

Data science can be used for a variety of things. It is great for predictive analysis, threat trend analysis, security information and event management (siem), or for analysing data such as logs. 

### Jupyter Notebooks

They are open-source documents containg code, text, and terminal functionality. They can easily be shared and executed across systems. They are a great what to explain and demonstrate concepts in cybersecurity. They can be considered instruction manuals as they are able to be executed one by one, step by step. 

## Capstone

### Objective 1 

Open the capstone workbook. 

### Objective 2 

Determine how many packets were captured. To do this the follwing command was used.

``` dataframe.count()``` 

In this notebook, dataframe is called df. This makes the command ```df.count()```. Going forward df will be used in place of dataframe. 

### Objective 3

What is the IP address that sent the most amount of traffic during the data capture?

The name of the data set is 'Source'. The following command was used to group the data

```df.groupby(['Source']).size()```

### Objective 4

What is the most frequent protocol?

The name of the data set is 'Protocol'. The following command was used to group the data

```df.groupby(['Protocol']).size()```