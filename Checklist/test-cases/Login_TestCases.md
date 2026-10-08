# Login Test Cases – SauceDemo

## TC-LOGIN-001 — Valid login
1. Enter correct username.
2. Enter correct password.
3. Click Login.
**Expected:** User is logged in.
**Status:** PASS

## TC-LOGIN-002 — Wrong password
1. Enter correct username.
2. Enter wrong password.
3. Click Login.
**Expected:** Error message is displayed.
**Status:** PASS

## TC-LOGIN-003 — Empty username
1. Leave username empty.
2. Enter correct password.
3. Click Login.
**Expected:** Error message is displayed.
**Status:** PASS

## TC-LOGIN-004 — Empty password
1. Enter correct username.
2. Leave password empty.
3. Click Login.
**Expected:** Error message is displayed.
**Status:** PASS

## Checklist
- Valid login — PASS
- Wrong password — PASS
- Empty username — PASS
- Empty password — PASS
