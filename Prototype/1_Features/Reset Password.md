# Feature: Reset Password 
## What should it do?
Create a password for first time login and forgot password. 

## Why does it matter?
Allow new users access their account. 

## Inputs
- e-mail address
- Reset password button
- Enter code
- Verify code button
- password 
- confirm password 
- reset password button

## Outputs
- token is created 
- user receives e-mail with verification code 
- redirect to enter code 
- code verified 
- redirect to set the password 
- password is saved in DB
- user is redirected to the login page 

## Key components
- Form
- Input fields
- Submit Buttons
- Email service for code
- Token
- DB

## Notes/Constraints
- Token for authentication 
- Verification code send to user's e-mail 