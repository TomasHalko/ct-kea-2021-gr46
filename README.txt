README.txt
Coderstrust Database

How to install MySQL Workbench:

1. Go to: https://dev.mysql.com/downloads/mysql/ 
2. Choose your operation system 
3. Download the provided installer 
4. Choose the "Developer default" setup type 
5. Click "Execute" 
6. Click "Next" 
7. Leave all the configuration on default and click "Next" 
8. Leave the settings on default and click "Next" 
9. Choose your root account password and repeat it 
10. Click "Next" and then "Execute" 
11. Click "Finish" 


Instructions for creating database from the DDL scripts provided:

1. Download the DDL files from GitHub - LINK
2. Open MySQL Workbench and establish a connection.
3. Press Ctrl+Shift+O and navigate to the downloaded SQL files.
4. Open and run the CreateCodersTrustDatabaseDDL.sql script to create the database.
5. Refresh the schemas in the navigator.
6. Select the coderstrust schema.
7. Press Ctrl+Shift+O, then select and run the CreateCodersTrustTablesDDL.sql
8. Press Ctrl+Shift+O, then select and run the CreateQuizzesViewDDL.sql


Instructions for populate the tables:

1. Download the DML files from GitHub - LINK
2. Open MySQL Workbench and establish a connection then select the coderstrust schema.
3. Press Ctrl+Shift+O and navigate to the downloaded SQL files.
4. Select the CodersTrustDML.sql and run the script to populate the tables.

Instructions for different select statements:

1. Download the DML files from GitHub - LINK
2. Open MySQL Workbench and establish a connection then select the coderstrust schema.
3. Press Ctrl+Shift+O and navigate to the downloaded SQL files.
4. Select the desired DML and run the script.