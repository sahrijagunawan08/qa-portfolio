# Login Feature – Test Cases

## Feature Description
Login functionality allows registered users to access the application using email and password.

---

## Test Cases

### TC-LOGIN-001
**Test Scenario:** Login with valid email and valid password  
**Precondition:** User is registered  

**Steps:**
1. Open login page
2. Enter valid email
3. Enter valid password
4. Click Login button

**Expected Result:**  
User is successfully logged in and redirected to dashboard

---

### TC-LOGIN-002
**Test Scenario:** Login with valid email and invalid password  

**Steps:**
1. Open login page
2. Enter valid email
3. Enter invalid password
4. Click Login button

**Expected Result:**  
Error message is displayed indicating incorrect credentials

---

### TC-LOGIN-003
**Test Scenario:** Login with unregistered email  

**Steps:**
1. Open login page
2. Enter unregistered email
3. Enter any password
4. Click Login button

**Expected Result:**  
Error message is displayed indicating user not found

---

### TC-LOGIN-004
**Test Scenario:** Login with empty email and password fields  

**Steps:**
1. Open login page
2. Leave email field empty
3. Leave password field empty
4. Click Login button

**Expected Result:**  
Validation message is displayed for required fields

---

### TC-LOGIN-005
**Test Scenario:** Login with valid email and empty password  

**Steps:**
1. Open login page
2. Enter valid email
3. Leave password field empty
4. Click Login button

**Expected Result:**  
Password required validation message is displayed

---

### TC-LOGIN-006
**Test Scenario:** Password field masked input  

**Steps:**
1. Open login page
2. Enter password in password field

**Expected Result:**  
Password characters are masked (hidden)

---

### TC-LOGIN-007
**Test Scenario:** Login button disabled when fields are empty  

**Steps:**
1. Open login page
2. Do not enter email and password

**Expected Result:**  
Login button is disabled or not clickable
