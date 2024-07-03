# Hotel_data_analysis-project

# read data => 
   1)   if we already have a csv file  pd.read_csv('file name').
      
   2)   and if we have a data from online  we need to fetch data like this   sns.load_dataset('url').


# observe data =>
    1) .isnull() only check data in boolean format (T/F).
    2) in dataset null values is like being blank or defined by NaN.
    3) .isnull().sum() will check how many null values available in a data 



# .info()  =>  displays the information of the data, like data types , class, columns & rows.

# .unique() => is used to display the unique values of the datasets.

# .nunique() =>   shows the size of the unique values of the data.

# sns.jointplot( ' ',data )  => shown the relationship between particular rows.

# sns.pairplot() => for pairwise relationships between variables & data.

# sns.kdeplot()  => for visualizing the distribution of observations in a dataset or histogram.

# sns.countplot() => shows the count of observations in each categorical bin using bars.
