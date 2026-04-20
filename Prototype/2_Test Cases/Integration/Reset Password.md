# Test plan: Reset Password

## Persona
People accessing the website for the first time or forgot password 

## Scenario
Reset password using verification code for authentication, email, password

## Tasks
1. Login as Independent user
2. Create a new account
3. Get code from email
4. Input code 
5. Login
## Success Metric
4/5 users reset password 

## Expected Outcome
Allow users to login

## Possible Failure Points
- 500 error

## Actual Result
The error message is shown on a different page 

## Issues Found
Redirected to other page before validation 
