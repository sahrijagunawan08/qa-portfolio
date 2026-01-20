# Login Test Cases – SauceDemo

## Application Information
- Application Name: SauceDemo
- URL: https://www.saucedemo.com/
- Feature Tested: Login
- Tester: Sahrija Gunawan

---

## TC-LOGIN-001
**Scenario:** Login with valid username and valid password  
**Test Data:**  
- Username: standard_user  
- Password: secret_sauce  

**Steps:**
1. Open https://www.saucedemo.com/
2. Enter valid username
3. Enter valid password
4. Click Login button

**Expected Result:**  
User is redirected to the Products page

---

## TC-LOGIN-002
**Scenario:** Login with valid username and invalid password  

**Steps:**
1. Open SauceDemo login page
2. Enter valid username
3. Enter invalid password
4. Click Login button

**Expected Result:**  
Error message displayed: "Username and password do not match"

---

## TC-LOGIN-003
**Scenario:** Login with invalid username and valid password  

**Steps:**
1. Open SauceDemo login page
2. Enter invalid username
3. Enter valid password
4. Click Login button

**Expected Result:**  
Error message displayed indicating invalid credentials

---

## TC-LOGIN-004
**Scenario:** Login with empty username and password  

**Steps:**
1. Open SauceDemo login page
2. Leave username field empty
3. Leave password field empty
4. Click Login button

**Expected Result:**  
Error message displayed: "Username is required"

---

## TC-LOGIN-005
**Scenario:** Login with empty password  

**Steps:**
1. Open SauceDemo login page
2. Enter valid username
3. Leave password field empty
4. Click Login button

**Expected Result:**  
Error message displayed: "Password is required"

---

## TC-LOGIN-006
**Scenario:** Verify password field masking  

**Steps:**
1. Open SauceDemo login page
2. Enter password into password field

**Expected Result:**  
Password characters are masked (shown as dots)

---

## TC-LOGIN-007
**Scenario:** Login with locked out user  

**Test Data:**  
- Username: locked_out_user  
- Password: secret_sauce  

**Steps:**
1. Open SauceDemo login page
2. Enter locked out username
3. Enter valid password
4. Click Login button

**Expected Result:**  
Error message displayed indicating the user is locked out
