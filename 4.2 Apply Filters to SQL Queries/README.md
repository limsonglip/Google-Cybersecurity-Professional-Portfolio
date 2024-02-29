# Scenario

I am a security professional at a large organization. Part of my job is to investigate security issues to help keep the system secure. I recently discovered some potential security issues that involve login attempts and employee machines.

My task is to examine the organization’s data in their employees and log_in_attempts tables. I’ll need to use SQL filters to retrieve records from different datasets and investigate the potential security issues.

# Step-By-Step Instructions

## Step 1: Access supporting material

Link to supporting material: <a href="Table formats.pdf">Table formats</a>

## Step 2: Retrieve after hours failed login attempts

I recently discovered a potential security incident that occurred after business hours. To investigate this, I need to query the log_in_attempts table and review after hours login activity. Use filters in SQL to create a query that identifies all failed login attempts that occurred after 18:00. (The time of the login attempt is found in the login_time column. The success column contains a value of 0 when a login attempt failed; you can use either a value of 0 or FALSE in your query to identify failed login attempts.)

Describe this query and how it works in the Retrieve after hours failed login attempts section. 

## Step 3: Retrieve login attempts on specific dates
A suspicious event occurred on 2022-05-09. To investigate this event, I want to review all login attempts which occurred on this day and the day before. Use filters in SQL to create a query that identifies all login attempts that occurred on 2022-05-09 or 2022-05-08. (The date of the login attempt is found in the login_date column.)

Describe this query and how it works in the Retrieve login attempts on specific dates section.

## Step 4: Retrieve login attempts outside of Mexico

There’s been suspicious activity with login attempts, but the team has determined that this activity didn't originate in Mexico. Now, I need to investigate login attempts that occurred outside of Mexico. Use filters in SQL to create a query that identifies all login attempts that occurred outside of Mexico. (When referring to Mexico, the country column contains values of both MEX and MEXICO, and I need to use the LIKE keyword with % to make sure my query reflects this.)

Describe this query and how it works in the Retrieve login attempts outside of Mexico section.

## Step 5: Retrieve employees in marketing

My team wants to perform security updates on specific employee machines in the Marketing department. I'm responsible for getting information on these employee machines and will need to query the employees table. Use filters in SQL to create a query that identifies all employees in the Marketing department for all offices in the East building. (The department of the employee is found in the department column, which contains values that include Marketing. The office is found in the office column. Some examples of values in this column are East-170, East-320, and North-434. I’ll need to use the LIKE keyword with % to filter for the East building.)

Describe this query and how it works in the Retrieve employees in Marketing section.

## Step 6: Retrieve employees in Finance or Sales
My team now needs to perform a different security update on machines for employees in the Sales and Finance departments. Use filters in SQL to create a query that identifies all employees in the Sales or Finance departments. (The department of the employee is found in the department column, which contains values that include Sales and Finance.)

Describe this query and how it works in the Retrieve employees in Finance or Sales section.

Step 7: Retrieve all employees not in IT

My team needs to make one more update to employee machines. The employees who are in the Information Technology department already had this update, but employees in all other departments need it. Use filters in SQL to create a query which identifies all employees not in the IT department. (The department of the employee is found in the department column, which contains values that include Information Technology.)

Describe this query and how it works in the Retrieve all employees not in IT section.

## Step 8: Finalize your document

To finalize the document and make its purpose clear to potential employers, be sure to complete the Project description and Summary sections. In the Project description section, give a general overview of the scenario and what you accomplish through SQL. Write two to four sentences. In the Summary section, provide a short summary of the previous tasks and connect them to the scenario. Write approximately two to four sentences.

View how I applied filters to SQL queries <a href="Apply Filters to SQL Queries.pdf">here</a>.
