# Login Test Cases – SauceDemo

## TC-LOGIN-001 — Valid login

**Preconditions:** Login page is open.

**Steps:**
1. Enter correct username.
2. Enter correct password.
3. Click Login.

**Expected Result:**
User is logged in and Products page is displayed.

**Actual Result:**
User is logged in and Products page is displayed.

**Status:** PASS


## TC-LOGIN-002 — Wrong password

**Preconditions:** Login page is open.

**Steps:**
1. Enter correct username.
2. Enter wrong password.
3. Click Login.

**Expected Result:**
Error message is displayed:
"Epic sadface: Username and password do not match any user in this service".

**Actual Result:**
Error message is displayed:
"Epic sadface: Username and password do not match any user in this service".

**Status:** PASS


## TC-LOGIN-003 — Empty username

**Preconditions:** Login page is open.

**Steps:**
1. Leave username empty.
2. Enter correct password.
3. Click Login.

**Expected Result:**
Error message is displayed:
"Epic sadface: Username is required".

**Actual Result:**
Error message is displayed:
"Epic sadface: Username is required".

**Status:** PASS


## TC-LOGIN-004 — Empty password

**Preconditions:** Login page is open.

**Steps:**
1. Enter correct username.
2. Leave password empty.
3. Click Login.

**Expected Result:**
Error message is displayed:
"Epic sadface: Password is required".

**Actual Result:**
Error message is displayed:
"Epic sadface: Password is required".

**Status:** PASS
