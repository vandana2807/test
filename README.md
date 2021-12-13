# Overview

You are asked to compare the sales profiles of two stores given some transaction data.
Expected output is a barplot that shows the relative sales of the different products for two stores (see below).

![alt text](https://github.com/qsic-interviews/data-science-template/blob/main/sale_profiles_plot.png)


# Details

- You will find simulated transaction data in in the repo file `test_data.tsv`.
- The barplot must show the relative sales (sold units per product divided by total sales) 
  for all products for the select stores.
- The stores to display are store-ids 1 and 3.
  
  
# Requirements

- The actual data is assumed to be much larger than `test_data.tsv` and does not fit into memory
  - therefore, the code cannot load the complete `test_data.tsv` file into memory!
  - but the transactions belonging to two stores will fit in memory
- The transaction data contain refunds (unit < 0) that must be filtered out
- The solution must be implemented in Python
- The code must produce a barplot with product names and exactly the same relative frequencies as shown  
  (but colors, orientation, bar width, bar order, font size and other plotting details do not matter)
- You cannot change the data file `test_data.tsv` 


# Notes

- There are more than two stores in the data set
- Names for the same product can very slightly, e.g. 'coffee_large', 'coffee-large'
- Apart from Python the usage of relevant libraries such as
  Numpy, Pandas, Pyspark, Dask, Matplotlib, Seaborn, Plotly, ...
  is encouraged if beneficial.
- The simpler, shorter and cleaner the code the better  
- Don't worry about comments but make the code readable


# Interview preparation

- Be prepared to explain and justify your implementation
- Think about the interpretation of the plot
  - What could go wrong?
  - What other, similar questions could be asked?
  - What other plots could be created from this data?
- Think about alternative implementations and their trade-offs
