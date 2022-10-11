
# HHA 507 - Assignment # 2

This repository represents the completion of HHA 507 Assignment # 2

Instructions:
Download the recently published dataset from healthdata.gov called “School Learning Modalities” - https://healthdata.gov/National/School-Learning-Modalities/aitj-yx37 - and place it into your new repo, and inside a new sub-folder inside of the repo
called ‘data’.

Create a Github repo called ‘hha-data-cleaning’ in your account and write a python script (.py file) that does the following:

- Loads thedata into python
- Prints the count of columns and rows
- Provides a print out of the column names
- Cleans the column names
- Cleans thestrings that might exist within each column
- Assesseswhite space or special characters
- Convertsthe column types to the correct types (e.g., DOB field is datetime and notobject)
- Look forduplicate rows and remove duplicate rows
- Assessmissingness (count of missing values per column)
- New datafield: attempt to create a new column called modality_inperson.  Thiscolumns hould contain a binary value of true or false. Try to write a function that takes in the old column name (learning modality), and recodes the value for a specific row to true, if the learning modality value is ‘in-person’, and recodes it to false if the value is either ‘remote’ or ‘hybrid’


