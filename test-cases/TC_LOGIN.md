# Login Module — Test Cases
**Site:** https://www.saucedemo.com/
**Tester:** Bermet Beisheeva

---

| Field | Value |
|-------|-------|
| **ID** | TC_LOGIN_001 |
| **Title** | Valid login with standard_user |
| **Preconditions** | User is on login page https://www.saucedemo.com/ |
| **Test Data** | Username: standard_user, Password: secret_sauce |
| **Steps** | 1. Enter "standard_user" in username field<br>2. Enter "secret_sauce" in password field<br>3. Click "Login" button |
| **Expected Result** | User is redirected to inventory page |
| **Actual Result** | User redirected to inventory page successfully |
| **Status** | ✅ Pass |
| **Bug ID** | — |

---

| Field | Value |
|-------|-------|
| **ID** | TC_LOGIN_002 |
| **Title** | Locked user sees error message |
| **Preconditions** | User is on login page |
| **Test Data** | Username: locked_out_user, Password: secret_sauce |
| **Steps** | 1. Enter "locked_out_user" in username field<br>2. Enter "secret_sauce" in password field<br>3. Click "Login" button |
| **Expected Result** | Error message: "Epic sadface: Sorry, this user has been locked out." User stays on login page |
| **Actual Result** | Error message displayed as expected. User cannot proceed |
| **Status** | ✅ Pass |
| **Bug ID** | — |

---

| Field | Value |
|-------|-------|
| **ID** | TC_LOGIN_003 |
| **Title** | Login with empty username field |
| **Preconditions** | User is on login page |
| **Test Data** | Username: (empty), Password: secret_sauce |
| **Steps** | 1. Leave username field empty<br>2. Enter "secret_sauce" in password field<br>3. Click "Login" button |
| **Expected Result** | Error message: "Epic sadface: Username is required" |
| **Actual Result** | Error message displayed: "Epic sadface: Username is required". User stays on login page |
| **Status** | ✅ Pass |
| **Bug ID** | — |

---

| Field | Value |
|-------|-------|
| **ID** | TC_LOGIN_004 |
| **Title** | Login with empty password field |
| **Preconditions** | User is on login page |
| **Test Data** | Username: standard_user, Password: (empty) |
| **Steps** | 1. Enter "standard_user" in username field<br>2. Leave password field empty<br>3. Click "Login" button |
| **Expected Result** | Error message: "Epic sadface: Password is required" |
| **Actual Result** | Error message displayed: "Epic sadface: Password is required". User stays on login page |
| **Status** | ✅ Pass |
| **Bug ID** | — |

---

| Field | Value |
|-------|-------|
| **ID** | TC_LOGIN_005 |
| **Title** | Login with wrong password |
| **Preconditions** | User is on login page |
| **Test Data** | Username: standard_user, Password: wrongpassword123 |
| **Steps** | 1. Enter "standard_user" in username field<br>2. Enter "wrongpassword123" in password field<br>3. Click "Login" button |
| **Expected Result** | Error message: "Epic sadface: Username and password do not match any user in this service" |
| **Actual Result** | Error message displayed as expected. User stays on login page |
| **Status** | ✅ Pass |
| **Bug ID** | — |

---

| Field | Value |
|-------|-------|
| **ID** | TC_LOGIN_006 |
| **Title** | Login with performance_glitch_user |
| **Preconditions** | User is on login page |
| **Test Data** | Username: performance_glitch_user, Password: secret_sauce |
| **Steps** | 1. Enter "performance_glitch_user" in username field<br>2. Enter "secret_sauce" in password field<br>3. Click "Login" button<br>4. Measure time until inventory page loads |
| **Expected Result** | User redirected to inventory page within 3 seconds |
| **Actual Result** | Page takes approximately 5-10 seconds to load |
| **Status** | ❌ Fail |
| **Bug ID** | BUG-001 |

---

| Field | Value |
|-------|-------|
| **ID** | TC_LOGIN_007 |
| **Title** | Login with problem_user |
| **Preconditions** | User is on login page |
| **Test Data** | Username: problem_user, Password: secret_sauce |
| **Steps** | 1. Enter "problem_user" in username field<br>2. Enter "secret_sauce" in password field<br>3. Click "Login" button |
| **Expected Result** | User redirected to inventory page |
| **Actual Result** | User redirected to inventory page but UI bugs present |
| **Status** | ❌ Fail |
| **Bug ID** | BUG-002 |

---

| Field | Value |
|-------|-------|
| **ID** | TC_LOGIN_008 |
| **Title** | Login with error_user |
| **Preconditions** | User is on login page |
| **Test Data** | Username: error_user, Password: secret_sauce |
| **Steps** | 1. Enter "error_user" in username field<br>2. Enter "secret_sauce" in password field<br>3. Click "Login" button |
| **Expected Result** | User redirected to inventory page |
| **Actual Result** | User redirected to inventory page but errors present |
| **Status** | ❌ Fail |
| **Bug ID** | BUG-003 |

---

| Field | Value |
|-------|-------|
| **ID** | TC_LOGIN_009 |
| **Title** | Login with visual_user |
| **Preconditions** | User is on login page |
| **Test Data** | Username: visual_user, Password: secret_sauce |
| **Steps** | 1. Enter "visual_user" in username field<br>2. Enter "secret_sauce" in password field<br>3. Click "Login" button |
| **Expected Result** | User redirected to inventory page |
| **Actual Result** | User redirected to inventory page but visual bugs present |
| **Status** | ❌ Fail |
| **Bug ID** | BUG-004 |
