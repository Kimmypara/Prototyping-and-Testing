---
date: 31/03/2026
tags:
---

# Unit Test

## Feature/Component
Verification code is verified 

## Purpose
To verify that code is
- not expired 
- not empty 
- invalid 

## Test Setup
Xampp , database,  form with a Verify Code button and received code by email

## Test Steps
1. Input code 
2. Verify Code button 

## Expected result
The system will verify if the users input a valid code otherwise, the error messages will show. 

## Actual Result
- Valid code 
	- Redirect you to reset the password 
- Empty code 
	- error message says that there is an empty field [[Empty_code.png]]
- Invalid code
	- Error message says that the code is invalid or expired [[invalid_code_error.png]]

## Issues Found
Nil

## Action
Nil 


