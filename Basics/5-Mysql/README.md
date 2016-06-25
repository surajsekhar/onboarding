## Common Commands
  * Login
  * Create Database
  * Create Table
  * Source an existing mysql - [Sample Dataset from the MySQL website](https://launchpad.net/test-db/+download)
  * SELECT table
  * SELECT + WHERE Clause
  * SELECT + GROUP Clause
  * SELECT + ORDER + Limit
  * Putting it all together
  * What is Normalization?
  * How do you build related tables? What's cascade?
  * What are triggers?
  * What are?
    * Primary Keys
    * Index
    * Foreign Key
    * Auto Increment

## References

[MySQL Basics - Digital Ocean](https://www.digitalocean.com/community/tutorials/a-basic-mysql-tutorial)
* The above link explains Setup for Ubuntu is different. For Mac use homebrew. [For initializing mysql](https://dev.mysql.com/doc/refman/5.5/en/default-privileges.html)
* Use only the command line for the task
* After youare comfotable with the command line, install [MySQL Workbench](https://www.mysql.com/products/workbench/)
  
## Tasks
  * Create a table `bank` to store bank details, etc. Create a table `branches` to store associated branch details
  * Add trigggers to this. What is a good use case of trigger in this scenario? (Add another table if required)
  * Add a new column for `bank` table 
  * Export your output as an `sql` file.
    * Sometimes you just want structure - what's the command?
    * Sometimes you also want data - what's the command?
  
  * On the data set downloaded in the above mentioned link, write the following queries:
    * Find second highest salary of Employee
    * Find Max Salary from each department
    * Find Avg Salary from each department
    * Find all the employee whose salary is more than the avg for his dept
    * Print the name of distinct employee whose DOB is between 01/01/1960 to 31/12/1975.
    * Find number of employees according to gender  whose DOB is between 01/01/1960 to 31/12/1975
    * Find name of employee whose name Start with ‘A’
    * Find all managers for the dept from the company whose salary is in top 2
    * Find employees hired between 1990 and 1995
    * All the employees who had more than three titles and list their titles
    * Employee details: Name, Title, Department, Department manager
    * Average salaries across departments for last 5 years
