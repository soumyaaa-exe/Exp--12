AIM:
To perform data analysis using Pandas by applying functions like value counting, percentage distribution, cross-tabulation, grouping, filtering, and sorting.

THEORY :
pd.read_csv(): Reads data from a CSV file and loads it into a DataFrame.

print(): Displays output on the console.

df['column']: Accesses a specific column from the DataFrame.

value_counts(): Counts frequency of each unique value in a column.

value_counts(normalize=True): Returns percentage distribution instead of counts.

*100: Converts proportion into percentage form.

pd.crosstab(): Creates a cross-tabulation table showing relationship between two categorical variables.

df.groupby(): Groups data based on one or more columns for aggregation.

groupby().value_counts(): Counts frequency of values within grouped categories.

pd.DataFrame(): Creates a DataFrame from structured data like dictionaries.

display(): Shows data in formatted tabular form (used in Jupyter/Colab).

df.unique(): Returns all unique values from a column.

df.nunique(): Returns the number of unique values in a column.

Filtering (df[condition]): Selects rows that satisfy a given condition.

df.sort_values(): Sorts the DataFrame based on a specific column.

groupby(['col1','col2']): Groups data based on multiple columns.

value_counts() with groupby: Gives frequency distribution within grouped categories.

CONCLUSION :
In this experiment, we analyzed datasets using Pandas functions like value_counts(), crosstab(), and groupby(). We explored frequency distribution, percentage calculation, and relationships between variables such as gender, department, and grades. Filtering and sorting helped in extracting meaningful insights. Overall, Pandas provides powerful tools for efficient data analysis and interpretation.
