# LAMIS3 - LAMISPlus ETL

This is an ETL tool built to migrate data from LAMIS3 to LAMISPlus v1.0. This tool was built using [Talend Open Studio for Big Data v7.3.1](https://www.talend.com/products/talend-open-studio/).

## Features

- Migrate data with a click
- Built for Windows and Unix
- Export summary after migration

## Components
There are various migration components available here. For a new migration, it is advisable to start with the facility migration and user migration before running the other migration components.
- Facility Migration: This component can be found at ./facility_migration/facility_migration_run[.bat/.sh]. 
- User Migration: This component can be found at ./user_migration/user_migration_run[.bat/.sh]
- Patient Migration: This component can be found at ./patient_migration/patient_migration_run[.bat/.sh]
- Laboratory Migration: This component can be found at ./laboratory_migration/laboratory_migration_run[.bat/.sh]

## Installation

To install, run the .bat/.sh file.

## How to change context parameters
If you want to change individual parameters in the context selection, edit the .bat/.sh file and add the following setting according to your need:

```sh
--context_param LAMISPlus_Login=postgres  
--context_param LAMISPlus_Password=postgres  
--context_param LAMISPlus_Database=lamisplus  
--context_param LAMIS3_Login=postgres  
--context_param LAMIS3_Password=postgres  
--context_param LAMIS3_Database=lamis3
```

## License

MIT

