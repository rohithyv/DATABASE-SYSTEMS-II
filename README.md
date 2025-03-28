📘 Project: Database Creation Using AWS CloudFormation and Oracle RDS
This project demonstrates the process of provisioning and interacting with relational databases (Oracle and PostgreSQL) on AWS using CloudFormation, and managing database schemas with Oracle SQL Developer and Data Modeler. It was developed as part of the Database Systems II course at The George Washington University.

🔧 Technologies Used
    • AWS CloudFormation – Infrastructure as Code (IaC) to deploy VPC, RDS Oracle, and PostgreSQL instances.
    • Oracle SQL Developer & Data Modeler – For database management, schema creation, and reverse engineering.
    • Oracle RDS – Hosting the HR database schema.
    • SQL & PL/SQL – For writing and executing queries on the HR database.

📁 Key Features
    1. Infrastructure Setup
        ◦ Created a VPC, public subnets, Oracle RDS, and PostgreSQL RDS using a CloudFormation YAML script.
        ◦ Managed stack creation, parameter customization (passwords, name prefix), and monitoring through AWS Console.
    2. Database Configuration
        ◦ Connected to Oracle RDS from a local SQL Developer.
        ◦ Created a new Oracle user (HR) and loaded the HR schema using Create_HR_Database_Schema.sql.
    3. SQL & PL/SQL Practice
        ◦ Ran SQL queries on the HR schema.
        ◦ Verified table creation and data retrieval (e.g., retrieving last_name, job_id, and salary from the employees table).
    4. Reverse Engineering the HR Schema
        ◦ Used Oracle SQL Developer Data Modeler to import the database structure and generate a relational diagram.
        ◦ Enabled visual schema analysis and design review.

📂 File Structure
    • Build_Single_AZ_Oracle_and_PostgreSQL_DBs.yaml – CloudFormation script for AWS resource deployment.
    • Create_User.sql – SQL script to create the Oracle HR user.
    • Create_HR_Database_Schema.sql – SQL script to generate HR database schema.
    • README.md – Project overview and documentation.

🧠 Learning Outcomes
    • Hands-on experience with AWS RDS and CloudFormation.
    • Practice using Oracle SQL Developer and Data Modeler tools.
    • Understand schema creation, user management, and data modeling.
    • Execute real-world SQL and PL/SQL queries using sample HR data.
