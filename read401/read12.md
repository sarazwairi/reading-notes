# 10 minutes to pandas

import:
```
In [1]: import numpy as np

In [2]: import pandas as pd
```

## Object creation

Series:Series is a one-dimensional labeled array capable of holding any data type .

DataFrame is a 2-dimensional labeled data structure with columns of potentially different types. You can think of it like a spreadsheet or SQL table, or a dict of Series objects. 

## Viewing data

pandas objects have a number of attributes enabling you to access the metadata

    shape: gives the axis dimensions of the object, consistent with ndarray

    Axis labels

            Series: index (only axis)

            DataFrame: index (rows) and columns


## Selection

The axis labeling information in pandas objects serves many purposes:

    Identifies data (i.e. provides metadata) using known indicators, important for analysis, visualization, and interactive console display.

    Enables automatic and explicit data alignment.

    Allows intuitive getting and setting of subsets of the data set.


## Missing data

pandas primarily uses the value np.nan to represent missing data. It is by default not included in computations.

## Operations

ith binary operations between pandas data structures, there are two key points of interest:

    Broadcasting behavior between higher- (e.g. DataFrame) and lower-dimensional (e.g. Series) objects.

    Missing data in computations.


## Merge

pandas provides various facilities for easily combining together Series and DataFrame objects with various kinds of set logic for the indexes and relational algebra functionality in the case of join / merge-type operations.

## Time series

pandas has simple, powerful, and efficient functionality for performing resampling operations during frequency conversion.

## Categoricals

The categorical data type is useful in the following cases:

    A string variable consisting of only a few different values. Converting such a string variable to a categorical variable will save some memory, see here.

    The lexical order of a variable is not the same as the logical order (“one”, “two”, “three”). By converting to a categorical and specifying an order on the categories, sorting and min/max will use the logical order instead of the lexical order, see here.

    As a signal to other Python libraries that this column should be treated as a categorical variable (e.g. to use suitable statistical methods or plot types).


