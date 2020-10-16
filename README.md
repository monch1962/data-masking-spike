[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/monch1962/data-masking-spike)

# data-masking-spike
Spike to investigate data masking options

# Instructions

## Load the sample database

`$ mysql -e "source mysqlsampledatabase.sql"`

will create a new database `classicmodels`

## Sample database schema

<object data="https://github.com/monch1962/data-masking-spike/blob/main/MySQL-Sample-Database-Diagram-PDF-A4.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://github.com/monch1962/data-masking-spike/blob/main/MySQL-Sample-Database-Diagram-PDF-A4.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://github.com/monch1962/data-masking-spike/blob/main/MySQL-Sample-Database-Diagram-PDF-A4.pdf">Download PDF</a>.</p>
    </embed>
</object>

## Show the contents of the 'employees' table

`$ mysql -e "USE classicmodels; SELECT * FROM employees;"`
