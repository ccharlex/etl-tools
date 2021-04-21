# LAMIS3 - LAMISPlus Patient ETL

This is an ETL tool built to migrate data from LAMIS3 to LAMISPlus v1.0. This tool was built using [Talend Open Studio for Big Data v7.3.1](https://www.talend.com/products/talend-open-studio/).

## Features

- Migrate data with a click
- Built for Windows and Unix
- Export summary after migration

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

