# Checkout Module — Test Cases
**Site:** https://www.saucedemo.com/
**Tester:** Bermet Beisheeva

---

| Field | Value |
|-------|-------|
| **ID** | TC_CHECKOUT_001 |
| **Title** | Verify checkout form fields for visual_user |
| **Preconditions** | User logged in as visual_user, 1 item in cart |
| **Test Data** | Username: visual_user, Password: secret_sauce |
| **Steps** | 1. Add item to cart<br>2. Click cart icon<br>3. Click Checkout<br>4. Observe form fields |
| **Expected Result** | Form has 3 fields: First Name, Last Name, Zip/Postal Code |
| **Actual Result** | Zip/Postal Code field is completely missing. Only First Name and Last Name visible |
| **Status** | ❌ Fail |
| **Bug ID** | BUG-010 |

---

| Field | Value |
|-------|-------|
| **ID** | TC_CHECKOUT_002 |
| **Title** | Verify Last Name field for problem_user |
| **Preconditions** | User logged in as problem_user, 1 item in cart |
| **Test Data** | Username: problem_user, Password: secret_sauce |
| **Steps** | 1. Add item to cart<br>2. Go to checkout<br>3. Click Last Name field<br>4. Type any text |
| **Expected Result** | Last Name field accepts text input |
| **Actual Result** | Last Name field does not accept any input. Field appears frozen |
| **Status** | ❌ Fail |
| **Bug ID** | BUG-011 |

---

| Field | Value |
|-------|-------|
| **ID** | TC_CHECKOUT_003 |
| **Title** | Verify checkout with empty cart |
| **Preconditions** | User logged in as standard_user, cart is empty |
| **Test Data** | Username: standard_user, Password: secret_sauce |
| **Steps** | 1. Do NOT add any items<br>2. Click cart icon<br>3. Click Checkout<br>4. Fill form with valid data<br>5. Click Continue |
| **Expected Result** | System prevents checkout with empty cart or shows warning message |
| **Actual Result** | User successfully completed checkout 
                     with empty cart. Order confirmed 
                     with $0.00 total. No warning shown |
| **Bug ID** | BUG-013 |

---
