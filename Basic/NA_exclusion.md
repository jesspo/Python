# R
R, basic commands

## NA
## Using your data without the NA

Ex: data, where you want to extract NA from one specific column and manage the data, for a mean.

```R
mean(data$column1, na.rm = TRUE)
```

And you will obtain the data of the column1 in your matrix, without the NA
