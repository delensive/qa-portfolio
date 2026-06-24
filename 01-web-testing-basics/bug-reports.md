# Bug Reports

Tested website: https://the-internet.herokuapp.com  
Date: 2026-06-19  
Tester: delensive

---

## Bug 1: Incorrect error message is shown when password is empty

**Page:** Form Authentication  
**Environment:** Chrome, desktop

**Steps to reproduce:**
1. Open https://the-internet.herokuapp.com/login
2. Enter username: `tomsmith`
3. Leave password field empty
4. Click the Login button

**Expected result:**  
The system should show a clear error message that the password field is required.

**Actual result:**  
The system shows a generic error message: `Your password is invalid!`

**Severity:** Low  
**Priority:** Low

**Comment:**  
The login is blocked correctly, but the error message is not specific enough. A clearer message would improve user experience.

---

## Bug 2: Incorrect error message is shown when username is empty

**Page:** Form Authentication  
**Environment:** Chrome, desktop

**Steps to reproduce:**
1. Open https://the-internet.herokuapp.com/login
2. Leave username field empty
3. Enter password: `SuperSecretPassword!`
4. Click the Login button

**Expected result:**  
The system should show a clear error message that the username field is required.

**Actual result:**  
The system shows a generic error message: `Your username is invalid!`

**Severity:** Low  
**Priority:** Low

**Comment:**  
The system blocks login correctly, but the message could be more helpful for the user.
