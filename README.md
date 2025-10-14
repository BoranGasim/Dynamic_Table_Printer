# Dynamic Table Printer Procedure

# Author  
**Boran Gasimli**

# Overview  
This PL/SQL project defines a procedure that can print all rows and columns of any table, no matter how many columns or what data types it has.  
It uses dynamic SQL with the DBMS_SQL package and BULK COLLECT to retrieve column definitions and display data dynamically.

# Key Features  
- Works with any table in the schema  
- Automatically detects column names and data types  
- Prints data in a formatted layout  

# How to Use  
1. Compile the procedure:
 Exec prc_method4('employees');
 "Employees" table is a sample from oracle hr schema
