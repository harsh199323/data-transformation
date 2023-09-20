# data-transformation
# It utilizes Python libraries such as Pandas, NumPy, and Matplotlib to import, process, and visualize the data. 

Code Sample 1: Birth Records Analysis

Data Import and Cleaning
Data Source: Birth records data is imported from a CSV file (2021-01-20_Dataset_Births.csv).
Data Cleaning:
Rows with missing values and those containing invalid day values (e.g., 99) are removed.
Invalid dates (e.g., February 30th and 31st) are filtered out.

Exploratory Analysis
Figure 1: Total Number of Births by Year and Gender
The total number of births is visualized by year and gender.
Insights:
Birth counts vary over the years.
Gender-wise trends can be observed.

Figure 2: Average Daily Births by Day of the Week and Decade
The average daily births are calculated by day of the week and decade.
Insights:
There is variation in birth counts throughout the week.
Trends over decades are displayed.

Figure 3: Average Daily Births by Date
The average daily births are visualized by month and day.
Insights:
Monthly patterns in birth counts can be observed.

Code Sample 2: Birth Names Analysis
Data Import and Cleaning
Data Source: Birth names data is imported from multiple text files.
Data Cleaning:
Column names are assigned to the DataFrame.
A 'year' column is added to track the year of each dataset.

Exploratory Analysis
Figure 4: Total Number of Births by Year and Gender
The total number of births is visualized by year and gender.
Insights:
Birth counts vary over the years.
Gender-wise trends are displayed.

Figure 5: Total Number of Births for Selected Names
The total number of births for names 'John,' 'Harry,' 'Mary,' and 'Marilyn' are visualized over time.
Insights:
Trends for specific names are presented.

Figure 6: Distribution of Names Ending with Each Letter
The distribution (in percentage) of names ending with each letter of the alphabet is visualized for the years 1910, 1960, and 2010.
Insights:
Changes in name endings are displayed.

Figure 7: Evolution of 'Leslie' Name Variants
The analysis focuses on various 'Leslie' name variants.
Insights:
Trends in 'Leslie' variants are presented over the years.
