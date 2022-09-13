# Palmoria-Group-Emp-Analysis

This project is in fulfillment of my capstone project at OUI Bootcamp. I assumed the role of an HR analyst working with employees data to identify key areas within the business that embroiled in issues bordering on gender inequality.

Data Source:
The database was gotten from Oui bootcamp and it contains two tables ‘Emp data’ and ‘bonus rules’. When merged together, they contain 1000 records and 12 attributes. The dataset contains information of employees, information such as name, department, gender, salary, location, rating, gender, percentage, bonus, payout. Other additional information about employees ratings and bonus are in the ‘bonus rules’ table.

# Data Wrangling
Loaded the dataset into Powerbi,cleaned and transformed the dataset in Power query classifying null genders as unspecified and removed workers not engaged with company anymore to identify active workers.
Removed duplicates from the 'Emp data' table which brought the dataset to a total of 943 rows,unpivoted the bonus attributes into two columns classifying the bonus into ratings and values before merging the tables.
Duplicated the 'Emp table to create a distinct department table to stand as dimension in my data modelling.

# Key Observations
 1. Palmoria group has a total of 943 workers, 440 females,464 males and 39 unspecified gender.
 2. The average salary of Male workers is higher than the female workers.
 3. Seven(7) out of total twelve(12) departments including Product management, legal, sales, support, training, accounting and marketing have high number of male    workers than women.
 4. Kaduna and Lagos have more male workers than females with Kaduna having a significant difference in gender gap.
 5. Male workers in Palmoria group have more poor and very poor ratings than their female counterpart.
 6. Kaduna has the highest total salary payout considering that it has more workers than Abuja and Lagos.
    
# Recommendations
1. Each department should be reviewed with  focus on departments with high male workers to ascertain the cause for gender gap i.e. Less qualifications, skills, abilities etc.
2. All location to be reviewed to vet out workers with multiple work locations .
3. Management to review salaries for each department and person to ensure genders with same department, position, skills are paid equally.
4. Management to ensure individual work performances are reviewed and rated to vet out workers with low performance ratings to give them room for improvement.
5. Management to consider skills enhancement programs for workers to help address and close skills gap.


