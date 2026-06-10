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
