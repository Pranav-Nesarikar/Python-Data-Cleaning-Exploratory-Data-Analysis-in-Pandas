# Python-Data-Cleaning-Exploratory-Data-Analysis-in-Pandas
  Exploratory data analysis (EDA) involves identifying patterns, understanding relationships between features, and dealing with outliers.

# During EDA, it's crucial to look for mistakes and missing values that need to be cleaned up in the future data cleaning process.
Visualization using libraries like Seaborn and Matplotlib is an essential part of the EDA process to gain a broader glimpse of the data.

✦Data set download and high level info extraction in Pandas

Downloading the specific data set is necessary for the tutorial
Extracting high level information using the info() function in Pandas

✦Identifying and handling missing values is crucial in data cleaning

By using DF.isnull().sum() we can find the number of missing values in each column
We must consider whether to impute with median values or delete missing data during the cleaning process

✦Sorting and filtering data based on specific criteria.

Using sort_values() to order data based on a specific column.
Using head() to view the top values after sorting.

✦Adjusting figure size and analyzing correlation in data visualization

Changing figure size using PLT dot RC params to improve visualization.
Analyzing correlation in population data and discovering unexpected correlations and lack of associations.

✦Grouping data for specific analysis
Grouping data by continent to focus on specific analysis goals
Examining growth rate and population density over a long span of data

✦Asia has the highest average population

The population density in Asia is far higher than any other continent, nearly double the average density
Each country in Asia makes up about one percent of the world population on average

✦Transposing DataFrames in Pandas
Transposing a DataFrame in Pandas swaps the columns and index, making it easy to visualize data differently.
After transposing, it's important to specify specific values and remove unwanted ones for a cleaner visualization.

✦Exploring trends in data over time
The data shows a significant increase in Asia and China's share of the global data
Other continents, especially Oceania, have shown minimal growth over the years

✦Identifying and analyzing outliers using box plots

Box plots help in visually identifying outliers in the dataset
Understanding and managing outliers is crucial for data analysis and cleaning

✦Understanding data types is crucial for focused analysis
data type filtering helps focus on specific analysis needs
data cleaning, data analysis, and visualization are key steps for data insight
