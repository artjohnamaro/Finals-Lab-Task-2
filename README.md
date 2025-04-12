# Finals Lab Task 2: [MySQL Database Creation](https://github.com/user-attachments/files/19716288/FINAL.LAB.TASK.2.pdf)
This portfolio showcases my comprehension of MySQL database development through the implementation of a basic student assignment submission system. It details the systematic construction of tables for students, assignments, and their corresponding submissions. The activity emphasizes the application of appropriate data types, relational structures, and constraints. These include primary keys, foreign keys, and composite keys to design a fully operational relational database schema.

## Step By Step Process
**Database Schema Design Instructions**
1. Creation of the student Table

- Define the attribute username as VARCHAR(50).

- Designate username as the Primary Key to ensure uniqueness for each student record.

2. Creation of the assignment Table

- Define shortname as VARCHAR(50) and assign it as the Primary Key.

- Define due_date as a DATE and specify it as NOT NULL to ensure all assignments have a deadline.

- Define url as VARCHAR(255) and allow it to be NULL, accommodating optional resource links.

3. Creation of the submission Table

- Define username and shortname both as VARCHAR(50) to establish identifiers for the student and the corresponding assignment.

- Define version as an INT to represent submission iterations.

- Define submit_date as a DATE with a NOT NULL constraint to ensure the presence of a submission date.

- Define data as TEXT to store the content of each submission.

- Establish a Composite Primary Key composed of (username, shortname, version) to uniquely identify each version of a submission.

- Add Foreign Key constraints on username and shortname, referencing the student and assignment tables respectively, to maintain referential integrity.

## QUERY STATEMENT
1. STUDENT TABLE
   - ![Image](https://github.com/user-attachments/assets/d043963f-5614-476c-8363-a2b0b1dd4ab8)
2. ASSIGNMENT TABLE
   - ![Image](https://github.com/user-attachments/assets/459f701e-7acc-4845-8793-c2356c751f7f)
3. SUBMISSION TABLE
   - ![Image](https://github.com/user-attachments/assets/12cdd9f8-1496-4285-adff-68fe5d779f20)
  
## TABLE STRUCTURE
1. STUDENT TABLE
   - ![Image](https://github.com/user-attachments/assets/3e805f34-8beb-4261-8e9e-6c4cfbeb5b86)
2. ASSIGNMENT TABLE
   - ![Image](https://github.com/user-attachments/assets/6ab761f3-e995-4df3-ae27-e23ae559bffe)
3. SUBMISSION TABLE
   - ![Image](https://github.com/user-attachments/assets/d7c6f9de-be11-4825-b2e6-8e541fd60062)

## ER DIAGRAM
 ![Image](https://github.com/user-attachments/assets/bee25883-7371-4128-8552-9d7d64099c81)
