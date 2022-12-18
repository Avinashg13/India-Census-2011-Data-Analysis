# India-Census-2011-Data-Analysis
Data analysis for India Census 2011
1) How will you hide the indexes of the dataframe.
2) How can we set the caption / heading on the dataframe.
3) Show the records related with the districts - New Delhi , Lucknow , Jaipur.
4) Calculate state-wise :
A. Total number of population.
B. Total no. of the population with different religions.
5) How many Male Workers were there in Maharashtra state ?
6) How to set a column as index of the dataframe ?
7a) Add a Suffix to the column names.
7b) Add a Prefix to the column names.
# Function that used to clean this Data are as follows
1) import pandas as pd -- To import Pandas library
2) pd.read_csv - To import the CSV file in Jupyter notebook
3) style.hide_index( ) - To hide the index of the dataframe.
4) style.set_caption('Description of the dataframe') - To give a caption to the dataframe.
5) isin( ) - To show all records including particular elements.
6) groupby(‘Col_1’)[‘Col_2’] .sum( )[‘value’] - GroupBy – Two Keys – Apply on Col_2 grouped by Col_1.
7) df[df.Col_1 == 'Element1']['Col_2'] - Filtering - Filter the records of the dataframe wrt to Element1 of Col1 and then showing results of Col2 only.
7a) set_index( ‘Col_Name’ ) - To set any column of a DF as an index.
7b) add_prefix(‘value_’) - To add prefix to the column name.
8) add_suffix(‘_value’) - To add suffix to the column name.

