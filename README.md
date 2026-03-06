## AIM:

### To learn about the Pandas library in Python and perform different operations on Series and DataFrames, including creating them, indexing, filtering data, making modifications, and carrying out statistical analysis.
---

## THEORY:
Pandas: Pandas is a powerful open-source Python library used for data manipulation, analysis, and cleaning. It provides flexible data structures that make it easy to handle structured data efficiently. Pandas is widely used in data science, machine learning, and data analysis tasks.

Series: A Series is a one-dimensional labeled array capable of holding data of any type such as integers, strings, or floating-point numbers. Each element in a Series is associated with an index, which helps in accessing and manipulating data easily.

DataFrame: A DataFrame is a two-dimensional tabular data structure consisting of rows and columns. It is similar to a spreadsheet or database table and can store different types of data in each column. DataFrames are the most commonly used structure in Pandas for storing and analyzing datasets.


1. display(): Used to present data in a well-organized tabular format in Jupyter Notebook or Google Colab.
2.  df.head(): Shows the first five rows of a DataFrame.
3. df.tail(): Shows the last five rows of a DataFrame.
4. df.shape: Returns the dimensions of the DataFrame as a tuple representing rows and columns.
5. df.ndim: Indicates the number of dimensions in the DataFrame.
6. df.size: Gives the total count of elements present in the DataFrame.
7. df.columns: Lists all the column names in the DataFrame.
8. df.dtypes: Displays the data type of each column.
9. df.loc[row]: Retrieves a row based on its label or index.
10. df.iloc[row, col]: Accesses a specific element using its positional index.
11. Adding Columns: New columns can be created by assigning values, for example df["Column"] = value_list.
12. Modifying Data: Data can be updated using indexing methods such as loc and iloc.
13. drop(): Used to delete rows or columns from a DataFrame.
14. Filtering: Allows selection of rows that satisfy certain conditions, for example df[df["Marks"] > 80].
15. Basic Statistics: Functions like mean(), min(), and max() are used to perform basic analysis on numerical data.
---

## CONCLUSION:
In this experiment, we studied different functionalities of the Pandas library, including the creation of Series and DataFrames and methods to access rows, columns, and specific elements. We also learned how to modify data, remove columns, and filter data using conditions. Furthermore, we applied statistical functions such as mean, minimum, and maximum. Overall, Pandas offers an efficient and flexible approach for managing and analyzing structured data.
