# CMPG-323-Project-4---29969263-
Branching Strategy
main: Production ready to be used Branch
hotfix: Branch to patch small issues
development Zones: Development branch where all functionality relating to Zones are done
development Devices: Development branch where all functionality relating to Devices are done
development Categories: Development branch where all functionality relating to Categories are done

Proces definition document

Login Process
Delete All Zones Process
Delete All Devices Process
Delete All Categories Process
Create All Zones From Workbook
Create All Devices From Workbook
Create All Categories From Workbook
Read All Zones From Workbook
Read All Devices From Workbook
Read All Categories From Workbook
Compare Input Data and Returned Data
Create Report

Requirements
Requires a text file to be placed in the root directory with the following format
Username
Password

Requires an excel Workbook in the root folder with the following sheets:
Device
Zone
Category
Test Results
All True/False Values in Worksheet need to be indicated with Uppercase

Order of opperation process
First Log in
The RPA will start by cleaning the websites data.
Then extract all the different sheets from the excel Workbook
Then the CRUD tests will be done on the Zone Data
Then the CRUD tests will be done on the Category Data
Then finally the CRUD tests will be done on the Device Data
Finally Logging out
