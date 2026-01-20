# Bug Report – Login Validation – SauceDemo

## Bug Title
Login validation only displays username error when password field is filled

## Environment
- Application: SauceDemo
- URL: https://www.saucedemo.com/
- Browser: Chrome (latest)
- OS: Windows 10

## Steps to Reproduce
1. Open SauceDemo login page
2. Leave Username field empty
3. Enter password: secret_sauce
4. Click Login button

## Expected Result
Validation message should clearly indicate required fields or guide user to complete login properly

## Actual Result
Error message displayed:
Epic sadface: Username is required

## Severity
Medium

## Priority
Medium

## Status
Open

## Notes
This behavior may confuse users because password was already filled but only username validation is shown.
