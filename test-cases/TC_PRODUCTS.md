# Products Module — Test Cases
**Site:** https://www.saucedemo.com/
**Tester:** Bermet Beisheeva

---

| Field | Value |
|-------|-------|
| **ID** | TC_PROD_001 |
| **Title** | Verify all products displayed for standard_user |
| **Preconditions** | User logged in as standard_user |
| **Test Data** | Username: standard_user, Password: secret_sauce |
| **Steps** | 1. Login as standard_user<br>2. Observe inventory page<br>3. Count products<br>4. Check each product has image, name, price, button |
| **Expected Result** | 6 products displayed with all elements correct |
| **Actual Result** | All 6 products displayed correctly with images, names, prices and buttons |
| **Status** | ✅ Pass |
| **Bug ID** | — |

---

| Field | Value |
|-------|-------|
| **ID** | TC_PROD_002 |
| **Title** | Verify sorting by name for problem_user |
| **Preconditions** | User logged in as problem_user, on inventory page |
| **Test Data** | Username: problem_user, Password: secret_sauce |
| **Steps** | 1. Click sorting dropdown<br>2. Select "Name (A to Z)"<br>3. Observe product order |
| **Expected Result** | Products sorted alphabetically A to Z |
| **Actual Result** | Products are NOT sorted. Order remains unchanged after selecting filter |
| **Status** | ❌ Fail |
| **Bug ID** | BUG-005 |

---

| Field | Value |
|-------|-------|
| **ID** | TC_PROD_003 |
| **Title** | Verify sorting by price for error_user |
| **Preconditions** | User logged in as error_user, on inventory page |
| **Test Data** | Username: error_user, Password: secret_sauce |
| **Steps** | 1. Click sorting dropdown<br>2. Select "Price (low to high)" |
| **Expected Result** | Products sorted from lowest to highest price |
| **Actual Result** | Error popup appears: "Sorting is broken! This error has been reported to Backtrace." No sorting occurs |
| **Status** | ❌ Fail |
| **Bug ID** | BUG-006 |
