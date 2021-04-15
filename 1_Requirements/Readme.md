# Requirements

## Introduction

Staff Management System is designed to keep a record of the staff employed in a company. The objective of the SMS program is to improve efficiency in management by providing a comprehensive framework to simplify the process of record-keeping. 

## Research
### Staff Management Software System Features and Benefits
   
   All details, personal or professional, regarding an employee are maintained in a functional system that aims to overcome the problems manual record-keeping systems encounter. The well-designed, functional database of the program stores information in a manner that the data is easily accessible and modifiable. 
   The Employee Management System is secure and reliable. It has invisible password typing and a dedicated login window. It is Password Protected and encrypted as a binary file. Furthermore, the database can be modified as per the user’s requirement i.e. records can easily be added, deleted or replaced.

### Benefits
Some of the benifits are

# Availability
It performs as readily available source of information between the organization and the employee.
Contact infornation,salary information,posts,work schedule,education etc., is what most database system consists of.

# Effeciency

These are very efficient.A member of the organization can easily retrieve information about his/her collegue whenever required, and that too on short notice.
one can avoid making calls to the employee out on vacation jjust to retrieve an address to send an important letter.

# Accuracy

Since the information is mostly fed in by the employees themselves you can be sure the information is accurate since its straight from the source.
Moreover, an employee can access their imformation at any time.

# Confidentiality

Specific information about the employee can not only be set to be kept private from public viewing but can also be set to be kept private from anyone .
it can insure availability, effeciency, accuracy,etc.,
You can worry less about managing bulky file or calling up your employees at inconvinent times.
 
 # Description
It is clear about Staff managing system from the below image.
![image](https://user-images.githubusercontent.com/81547783/114836305-24338480-9df0-11eb-8847-4ec3a9ada178.png)



    
## SWOT ANALYSIS
![image](https://user-images.githubusercontent.com/81547783/114835752-86d85080-9def-11eb-80a4-ad6e968eb2da.png)

# 4W&#39;s and 1&#39;H

## Who:

Many MNC's and also used in many sectors

## What:

For many industries it becomes a tedious task to manage every employee record  with hand written file system

## When:

It can be used for many situations like data deletion, retrival,insertion etc
## Where:

In many Fields this can be used.

## How:

It is easy to access for everyone.

# Detail requirements
## High Level Requirements:
| ID | Description | Category | Status | 
| ----- | ----- | ------- | ---------|
| HR01 | User shall be able to add new employee record | Techincal | IMPLEMENTED | 
| HR02 | User shall be able to read a employee record | Techincal |  IMPLEMENTED  |
| HR03 | User shall be able to update a employee record | Techincal |  IMPLEMENTED  |
| HR04 | User shall be able to delete a employee record | Techincal |  IMPLEMENTED  |
| HR05 | User shall be able to save records in a file | Techincal |  IMPLEMENTED  |
| HR06 | User shall be able to read data from a file | Techincal |  IMPLEMENTED  |
| HR07 | Data should not be lost in case of faliure | Scenario | FUTURE |
| HR08 | Data should always be stored when closing the system | Scenario |  IMPLEMENTED |


##  Low level Requirements:
| ID | Description | HLR ID | Status (Implemented/Future) |
| ------ | --------- | ------ | ----- |
| LR01 | (1). New record shall be added by providing all the asked information                                                                                                    (2). Id should be unique and validated from persistant file or else employee record should not be accepted. | HR01 |  IMPLEMENTED  |
| LR02 | Reading employee data should be possible in 2 ways (1). first being by searching by id of employee (2). By printing all the records available | HR02 |  IMPLEMENTED |
| LR03 | While reading all the records, only 10 records per page should be visible and should add 10 more if user wants to see more | HR02 | FUTURE |
| LR04 | If user searches for an invalid ID "No Record Found" message should be displayed | HR02 |  IMPLEMENTED  |
| LR05 | User need to search by id for the employee record to be updated, if no such record is available then "No Record Found" Message should be displayed | HR03 |  IMPLEMENTED  |
| LR06 | User need to search by id for the employee record to be deleted, if no such record is available then "No Record Found" Message should be displayed | HR04 |  IMPLEMENTED  |
| LR05 | User shall be able to save the files, if file already exists then it should append to file and should not overwrite it and if file does not exists then it should create a new file | HR05 |  IMPLEMENTED  |
| LR06 | If opening the file fails, then the system shloud prompt the message "Unable to access file" and should not end the program execution | HR05, HR06, HR07, HR08 |  IMPLEMENTED  |
| LR07 | When user Log off the system perform check and save data to file (1). If new data in inserted add it to file (2). If New data is not inserted do not add anything to file | HR08 |  IMPLEMENTED  |
