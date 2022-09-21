
# Extract Large Transactions from UPSL Reports

This project contains a UiPath library for automating the extraction of large Unified Payment Services Limited (UPSL) transactions and converting them to a datatable for further processing.


## Authors

- [@Olayeni Anifowose](https://github.com/olayeni45)


## Installation

* Download the library folder and publish the .xaml file to your local UiPath Orchestrator.
* Install the package as an activity in your project.
* Configure the activity with the required arguments.
    
## Arguments

To run this activity, you will need to configure the following arguments:

`File_Path`\
Directory containing the report files.\
**Direction:** In

`Report_File`\
The absolute path of the report file.\
**Direction:** In

`Worksheet`\
The name of the worksheet to be extracted.\
**Direction:** In

`Datatable`\
The datatable containing the transactions.\
**Direction:** Out
## Screenshots

![Activity Screenshot](https://res.cloudinary.com/edconnect/image/upload/v1663784404/Github/Extract_Transactions_rr70tw.png)


## Acronyms

* **UPSL**: Unified Payment Services Limited
