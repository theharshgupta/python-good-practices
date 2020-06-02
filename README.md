# Pandas Dataframes 
## Adding a new column 
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.assign.html
```
df = df.assign(column_name=column_values)
```

## Updating column based on condition 
```
df.loc[df[column_name].str.contains('value'), 'check_value'] = NEW_VALUE
```
