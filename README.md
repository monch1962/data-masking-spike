[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/monch1962/data-masking-spike)

# data-masking-spike
Spike to investigate data masking options

# Examples

## MySQL

### Load the sample database

`$ mysql -e "source mysqlsampledatabase.sql"`

will create a new database `classicmodels`

### Sample database schema

![GitHub Logo](https://github.com/monch1962/data-masking-spike/blob/main/MySQL-Sample-Database-Diagram-PDF-A4.png)

### Show the contents of the 'employees' table

`$ mysql -e "USE classicmodels; SELECT * FROM employees;"`
