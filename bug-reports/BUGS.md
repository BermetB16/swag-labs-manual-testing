# Bug Reports
**Site:** https://www.saucedemo.com/
**Tester:** Bermet Beisheeva

---

## BUG-001: Performance glitch user — slow page load

| Field | Value |
|-------|-------|
| **ID** | BUG-001 |
| **Title** | performance_glitch_user experiences 5-10 second delay on login |
| **Severity** | Minor |
| **Priority** | Low |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Go to saucedemo.com<br>2. Login as performance_glitch_user / secret_sauce<br>3. Click Login |
| **Expected** | Page loads within 3 seconds |
| **Actual** | Page takes 5-10 seconds to load |

---

## BUG-002: problem_user — UI bugs on inventory page

| Field | Value |
|-------|-------|
| **ID** | BUG-002 |
| **Title** | problem_user sees wrong product images on inventory page |
| **Severity** | Major |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as problem_user / secret_sauce<br>2. Observe inventory page |
| **Expected** | All product images correct |
| **Actual** | All product images are wrong/broken |

---

## BUG-003: error_user — UI bugs on inventory page

| Field | Value |
|-------|-------|
| **ID** | BUG-003 |
| **Title** | error_user experiences multiple errors on inventory page |
| **Severity** | Major |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as error_user / secret_sauce<br>2. Observe inventory page |
| **Expected** | Inventory page works correctly |
| **Actual** | Multiple errors present — sorting broken, remove button not working |

---

## BUG-004: visual_user — visual bugs on inventory page

| Field | Value |
|-------|-------|
| **ID** | BUG-004 |
| **Title** | visual_user sees misplaced elements on inventory page |
| **Severity** | Major |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as visual_user / secret_sauce<br>2. Observe inventory page |
| **Expected** | All elements in correct positions |
| **Actual** | Cart icon misplaced, one product image wrong |

---

## BUG-005: problem_user — sorting not working

| Field | Value |
|-------|-------|
| **ID** | BUG-005 |
| **Title** | Sorting by name does not work for problem_user |
| **Severity** | Major |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as problem_user / secret_sauce<br>2. Click sort dropdown<br>3. Select "Name (A to Z)" |
| **Expected** | Products sorted alphabetically |
| **Actual** | Products remain in original order. No sorting occurs |

---

## BUG-006: error_user — sorting throws error

| Field | Value |
|-------|-------|
| **ID** | BUG-006 |
| **Title** | Sorting shows error popup for error_user |
| **Severity** | Critical |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as error_user / secret_sauce<br>2. Click sort dropdown<br>3. Select any sort option |
| **Expected** | Products sorted correctly |
| **Actual** | Error popup: "Sorting is broken! This error has been reported to Backtrace." |

---

## BUG-007: problem_user — add to cart limited to 2 items

| Field | Value |
|-------|-------|
| **ID** | BUG-007 |
| **Title** | Add to Cart button stops working after 2 items for problem_user |
| **Severity** | Critical |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as problem_user / secret_sauce<br>2. Add first item to cart<br>3. Add second item to cart<br>4. Try to add third item |
| **Expected** | All 6 items can be added to cart |
| **Actual** | Only 2 items can be added. Button stops responding after 2 items |

---

## BUG-008: error_user — remove from cart not working

| Field | Value |
|-------|-------|
| **ID** | BUG-008 |
| **Title** | Remove button does not remove item from cart for error_user |
| **Severity** | Critical |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as error_user / secret_sauce<br>2. Add item to cart<br>3. Go to cart page<br>4. Click Remove button |
| **Expected** | Item removed from cart. Badge updates to 0 |
| **Actual** | Item remains in cart after clicking Remove. Badge still shows 1 |

---

## BUG-009: visual_user — checkout button misplaced

| Field | Value |
|-------|-------|
| **ID** | BUG-009 |
| **Title** | Checkout button floating in wrong position for visual_user |
| **Severity** | Major |
| **Priority** | Medium |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as visual_user / secret_sauce<br>2. Add item to cart<br>3. Go to cart page<br>4. Observe Checkout button |
| **Expected** | Checkout button at bottom of cart page |
| **Actual** | Checkout button floating in top right corner of page |

---

## BUG-010: visual_user — zip field missing on checkout

| Field | Value |
|-------|-------|
| **ID** | BUG-010 |
| **Title** | Zip/Postal Code field missing on checkout for visual_user |
| **Severity** | Critical |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as visual_user / secret_sauce<br>2. Add item to cart<br>3. Go to checkout<br>4. Observe form fields |
| **Expected** | Form has 3 fields: First Name, Last Name, Zip/Postal Code |
| **Actual** | Zip/Postal Code field completely missing |

---

## BUG-011: problem_user — Last Name field frozen

| Field | Value |
|-------|-------|
| **ID** | BUG-011 |
| **Title** | Last Name field does not accept input for problem_user |
| **Severity** | Critical |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as problem_user / secret_sauce<br>2. Add item to cart<br>3. Go to checkout<br>4. Click Last Name field<br>5. Try to type |
| **Expected** | Field accepts text input |
| **Actual** | Field completely frozen. No input accepted |

---

## BUG-012: standard_user — checkout allowed with empty cart

| Field | Value |
|-------|-------|
| **ID** | BUG-012 |
| **Title** | User can proceed to checkout with empty cart |
| **Severity** | Minor |
| **Priority** | Medium |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as standard_user / secret_sauce<br>2. Do not add any items<br>3. Click cart icon<br>4. Click Checkout |
| **Expected** | Warning: "Cart is empty" or Checkout button disabled |
| **Actual** | User proceeds to checkout with empty cart. No warning shown |

---

## BUG-013: problem_user — no price calculation on checkout

| Field | Value |
|-------|-------|
| **ID** | BUG-013 |
| **Title** | Price summary and tax not shown on checkout for problem_user |
| **Severity** | Critical |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as problem_user / secret_sauce<br>2. Add items to cart<br>3. Go to checkout<br>4. Complete form<br>5. Click Continue |
| **Expected** | Checkout overview shows item total, tax and final total |
| **Actual** | No price summary, tax or total calculation displayed |
