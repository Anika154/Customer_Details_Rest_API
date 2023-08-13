# Customer_Details_Rest_API

## How to run this project
* Clone this project
* Open with Postman / Command Shell
* Run Command:
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json 
```
* Run Command for Report:
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra 
```


## Technology Used:
* Postman
* Newman

## Prerequisite:
* Jdk
* Node Js
* Newman
* HTML Report Library

## Newman and Report Installation Process:
* Newman Install Command:
```console 
npm install -g newman-reporter-htmlextra
```
* Newman Html Report Install Command:
```console 
npm install -g newman-reporter-htmlextra
```
## API Documentation:
* https://documenter.getpostman.com/view/28998398/2s9Xy5MAqr
## Test case list:
1. ### Create Customer
	> Create Data Sets Using the Dynamic Random Variables.
2. ### Verify Created Customer Details
	> In the test case you need to validate the following field values:
 	1. > First Name
 	2. > Middle Name
 	3. > Last Name
 	4. > Date of Birth

3. ### Update Customer
	> In the test case you need to validate the following field values:
 	1. > Only Message
4. ### Verify Verify Updated Customer Details
	> In the test case you need to validate the following field values:
	1. > First Name
 	2. > Middle Name
	3. > Last Name
 	4. > Date of Birth

5. ### Create Technical skills Create Customer Address
	> In the test case you need to validate the following field values:
	1. > Only Message

6. ### Create a Customer Address
	> In the test case you need to validate the following field values:
	1. > Only Message

7. ### Get the Customer's Full Details
	> In the test case you need to validate the following field values:
	1. > First Name
	2. > Middle Name
	3. > Last Name
	4. > Date of Birth
	5. > Language
	6. > Year Of Experience
	7. > Last Used Date
	8. > House Number
	9. > City
	10. > State
	11. > Country
	12. > Std Code
	13. > Home Address
	14. > Mobile

8. ### Delete Specific Customer
	> In the test case you need to validate the following field values:
	1. > Only Message
## Newman Report Summary:
![Report](https://github.com/Anika154/Customer_Details_Rest_API/assets/54212195/91043030-3b8c-4da0-ae28-b519a1cee6e5)
![Report](https://github.com/Anika154/Customer_Details_Rest_API/assets/54212195/a6a3a781-7502-4776-860b-4f35f0e4be28)











  
