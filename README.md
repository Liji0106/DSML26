# Exploratory Data Analysis


Providing a dataset of employees working in ABC company. It consists of 458 rows and 9 columns. The company needs the detailed report and explanation of their employees in each team, also need to identify the following:

1. Determine the distribution of employees across each team and calculate the percentage split relative to the total number of employees.
2. Segregate employees based on their positions within the company.
3. Identify the predominant age group among employees. 
4. Discover which team and position have the highest salary expenditure.
5. Investigate if there's any correlation between age and salary, and represent it visually.

# Data Processing
The "height" column has been corrected by inserting random integers between 150 and 180 in its place. Additionally, the description, null values, duplicate values, and dataset information were examined. With the exception of College and Salary, the majority of the columns have values. Salary has 11 null values and college has 84. There are no duplicate rows in the dataset.

# Data Analysis
1) Distribution of employees accross team
   Analyzed the number of workers on each team and found that the New Orleans Pelicans have the most workers (19).

2) Employees seggregation based on position
   Based on the position, the highest count of employee is for the position is 'SG' i.e. 102 employee

3) Predominant age group
   Determined which age group is most prevalent in the firm by using the cut() method on an existing dataframe to create a new dataframe specifically for that age group.
    There are more workers in the company who are in the 20–29 age group (334), compared to 119 workers in the 30-39 age bracket. There are just three people in the 40–49 age bracket, and nobody above 50.

4) Salary expenditure
  The total pay expense was determined for each position and team.
   Findings: The Cleveland Cavaliers have the highest salary spending (72902950), while the Washington Wizards have the lowest salary expenditure (76328636). 'C', the position with the highest salary expenditure (466377332), and 'SG', the position with the lowest salary expenditure (396976258),

5) Age and salary correlation
  The correlation coefficient between age and pay is 0.214. There is a correlation between employee age and salary because the correlation coefficient is positive. 
   This indicates that older workers make more money than younger individuals.

# Conclusion
  The provided dataset contains accurate information on ABC Company workers. The aforementioned insights have the potential to both identify trends and aid in the development of enterprises.
