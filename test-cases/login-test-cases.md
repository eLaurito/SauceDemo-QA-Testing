# SauceDemo — Login Test Cases

## Test Environment

* **Application:** SauceDemo
* **Module:** Login
* **Test type:** Functional / Validation testing
* **Tester:** Ezequiel Laurito

---

## TC-01 — Login with empty fields

**Precondition:** User is on the login page.

**Steps:**

1. Leave Username empty.
2. Leave Password empty.
3. Click **Login**.

**Expected result:**
A message indicating that the username is required should be displayed.

**Actual result:**
`Epic sadface: Username is required`

**Status:** ✅ PASS

---

## TC-02 — Empty username

**Precondition:** User is on the login page.

**Steps:**

1. Leave Username empty.
2. Enter a password.
3. Click **Login**.

**Expected result:**
A message indicating that the username is required should be displayed.

**Actual result:**
`Epic sadface: Username is required`

**Status:** ✅ PASS

---

## TC-03 — Empty password

**Precondition:** User is on the login page.

**Steps:**

1. Enter a valid username.
2. Leave Password empty.
3. Click **Login**.

**Expected result:**
A message indicating that the password is required should be displayed.

**Actual result:**
`Epic sadface: Password is required`

**Status:** ✅ PASS

---

## TC-04 — Valid username with incorrect password

**Precondition:** User is on the login page.

**Steps:**

1. Enter a valid username.
2. Enter an incorrect password.
3. Click **Login**.

**Expected result:**
Login should be rejected and an error message should be displayed.

**Actual result:**
`Epic sadface: Username and password do not match any user in this service`

**Status:** ✅ PASS

---

## TC-05 — Incorrect username with valid password

**Precondition:** User is on the login page.

**Steps:**

1. Enter an incorrect username.
2. Enter a valid password.
3. Click **Login**.

**Expected result:**
Login should be rejected and an error message should be displayed.

**Actual result:**
`Epic sadface: Username and password do not match any user in this service`

**Status:** ✅ PASS

---

## TC-06 — Incorrect username and password

**Precondition:** User is on the login page.

**Steps:**

1. Enter an incorrect username.
2. Enter an incorrect password.
3. Click **Login**.

**Expected result:**
Login should be rejected and an error message should be displayed.

**Actual result:**
`Epic sadface: Username and password do not match any user in this service`

**Status:** ✅ PASS
