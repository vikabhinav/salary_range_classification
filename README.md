Context
Salary range is the range of pay established by employers to pay to employees performing a particular job or function. Salary range generally has a minimum pay rate, a maximum pay rate, and a series of mid-range opportunities for pay increases.
The salary range is determined by market pay rates, organization, department, union, type and domain of jobs, established through market pay studies, for people doing similar work in similar industries in the same region of the country.
Pay rates and salary ranges are also set up by individual employers and recognize the level of education, knowledge, skill, and experience needed to perform each job.

About Dataset
Its a database of the salary and benefits paid to City employees since fiscal year 2013.
This data is summarized and presented on the Employee Compensation report hostedat http://openbook.sfgov.org .

The features of dataset are as given below -
Year Type - Fiscal (July through June) or Calendar (January through December)
Year - An accounting period of 12 months. The City and County of San Francisco operates on a fiscal year that begins on July 1 and ends on June 30 the following year. The Fiscal Year ending June 30, 2012 is represented as FY 2011-2012.
Organization Group Code - Org Group is a group of Departments. For example, the Public Protection Org Group includes departments such as the Police, Fire, Adult Probation, District Attorney, and Sheriff.
Organization Group - Org Group is a group of Departments. For example, the Public Protection Org Group includes departments such as the Police, Fire, Adult Probation, District Attorney, and Sheriff.
Department Code- Departments are the primary organizational unit used by the City and County of San Francisco. Examples include Recreation and Parks, Public Works, and the Police Department.
Department - Departments are the primary organizational unit used by the City and County of San Francisco. Examples include Recreation and Parks, Public Works, and the Police Department.
Union Code- Unions represent employees in collective bargaining agreements. A job belongs to one union, although some jobs are unrepresented (usually temporarily).
Union - Unions represent employees in collective bargaining agreements. A job belongs to one union, although some jobs are unrepresented (usually temporarily).
Job Family Code - Job Family combines similar Jobs into meaningful groups.
Job Family - Job Family combines similar Jobs into meaningful groups.
Job Code - Jobs are defined by the Human Resources classification unit. Examples include gardeners, police officers, and accountants.
Job - Jobs are defined by the Human Resources classification unit. Examples include gardeners, police officers, and accountants.
Employee Identifier - Each distinct number in the “Employee Identifier” column represents one employee. These identifying numbers are not meaningful but rather are randomly assigned for the purpose of building this dataset. The column does not appear on the Employee Compensation report hosted on openbook.sfgov.org, but that report does show one row for each employee. Employee ID has been included here to allow users to reconstruct the original report. Note that each employee’s identifier will change each time this dataset is updated, so comparisons by employee across multiple versions of the dataset are not possible.
Overtime - Amounts paid to City employees working in excess of 40 hours per week.
Other Salaries - Various irregular payments made to City employees including premium pay, incentive pay, or other one-time payments.
Retirement - City contributions to employee retirement plans.
Health/Dental - City-paid premiums to health and dental insurance plans covering City employees. To protect confidentiality as legally required, pro-rated citywide averages are presented in lieu of employee-specific health and dental benefits.
Other Benefits - Mandatory benefits paid on behalf of employees, such as Social Security (FICA and Medicare) contributions, unemployment insurance premiums, and minor discretionary benefits not included in the above categories.
Total Benefits - The sum of all benefits paid to City employees.
Class- Class of Normal salaries paid to permanent or temporary City employees.
Note: In the Class variable - 1 : Low range salary
2 : Mid range salary
3 : High range salary

Problem Statement -
You need to classify the normal salary range of different employees based on information provided by different features in the dataset.
The Class variable provides the range of salary into 3 categories that are low, mid and high range.
You have been given a train data and the test data.

Submission Format -
You need to submit the csv format file with 2 columns in the order - ID and Class using the test dataset.
Please make sure the format of your file is exactly same as mentioned above(order, letter format etc).
