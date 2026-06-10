# Test Cases

## TC_LOGIN_001

Scenario:
Verify login using valid customer credentials.

Precondition:
Customer account should be active.

Steps:
1. Open application
2. Enter valid User ID
3. Enter valid Password
4. Click Login

Expected Result:
Customer should be redirected to Account Summary page.

Actual Result:
Customer redirected successfully.

Status:
Pass

---

## TC_LOGIN_002

Scenario:
Verify login using invalid password.

Steps:
1. Enter valid User ID
2. Enter incorrect Password
3. Click Login

Expected Result:
Application should display invalid credentials message.

Actual Result:
Error message displayed.

Status:
Pass

---

## TC_LOGIN_003

Scenario:
Verify account lock after 5 failed login attempts.

Expected Result:
Account should be locked after 5 failed attempts.

Actual Result:
Account locked after 3 attempts.

Status:
Fail

Defect ID:
BUG_001

---

## TC_FT_001

Scenario:
Verify fund transfer to registered beneficiary.

Expected Result:
Transaction should complete successfully.

Actual Result:
Transaction completed successfully.

Status:
Pass

---

## TC_FT_002

Scenario:
Verify transfer amount greater than available balance.

Expected Result:
Transaction should be rejected.

Actual Result:
Transaction rejected with proper message.

Status:
Pass
---

## TC_BEN_001

Scenario:
Verify addition of new beneficiary with valid details.

Expected Result:
Beneficiary should be added successfully.

Actual Result:
Beneficiary added successfully.

Status:
Pass

---

## TC_BEN_002

Scenario:
Verify duplicate beneficiary account number validation.

Expected Result:
System should prevent duplicate beneficiary addition.

Actual Result:
Duplicate beneficiary added successfully.

Status:
Fail

Defect ID:
BUG_002

---

## TC_TXN_001

Scenario:
Verify transaction history for last 30 days.

Expected Result:
Transactions should be displayed correctly.

Actual Result:
Transactions displayed successfully.

Status:
Pass

---

## TC_PWD_001

Scenario:
Verify password change functionality.

Expected Result:
Password should be updated successfully.

Actual Result:
Password updated successfully.

Status:
Pass

---

## TC_PWD_002

Scenario:
Verify password complexity validation.

Expected Result:
System should reject weak password.

Actual Result:
Weak password accepted.

Status:
Fail

Defect ID:
BUG_005
