# Things that took tons of time to figure out

## how to store numeric values, and also keep any missing values as NaN

this is the code that converts a data type to numeric type, such that missing values are stored as 'NaN'

```code
## remove commas from the strings created
data_set[number_columns] = data_set[number_columns].replace(',','', regex=True)
# print(data_set)
## set nan to NaN
data_set[number_columns] = data_set[number_columns].replace('nan','NaN', regex=True)
# print(data_set)
## convert to float64
data_set[number_columns] = data_set[number_columns].astype('float64')
data_set
```

to make all stirngs in a column capitalised
```code
data_set[column] = data_set[column].str.capitalize()
```