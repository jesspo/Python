# R
R, basic commands

## NA - Using your data without the NA

Ex: data, where you want to extract NA from one specific column and manage the data, for a mean.

```R
mean(data$column1, na.rm = TRUE)
```

And you will obtain the data of the column1 in your matrix, without the NA

## Filtering data from a Matrix

Install dplyr

```R
install.packages(dplyr)

library(dplyr)
```

Ex: you want to have only the values in column1 higher than 30 and in column2 higher than 8

```R
filter(data, data$column1 >30, data$column2 >8)
```

and you will obtain a new subset, only with the data which has those characteristics
