# Bug Reports
**Site:** https://www.saucedemo.com/
**Tester:** Bermet Beisheeva

---

## BUG-001: performance_glitch_user — slow page load

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

## BUG-002: problem_user — wrong product images

| Field | Value |
|-------|-------|
| **ID** | BUG-002 |
| **Title** | problem_user sees wrong product images on inventory page |
| **Severity** | Major |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as problem_user / secret_sauce<br>2. Observe inventory page |
| **Expected** | All product images displayed correctly |
| **Actual** | All product images are wrong/broken |

---

## BUG-003: error_user — multiple errors on inventory page

| Field | Value |
|-------|-------|
| **ID** | BUG-003 |
| **Title** | error_user cannot remove items from inventory page |
| **Severity** | Critical |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as error_user / secret_sauce<br>2. Add item to cart<br>3. Click Remove button on inventory page |
| **Expected** | Item is removed from cart. Cart badge updates correctly |
| **Actual** | Item is NOT removed. Remove button does not work on inventory page |

---

## BUG-004: visual_user — visual bugs on inventory page

| Field | Value |
|-------|-------|
| **ID** | BUG-004 |
| **Title** | visual_user sees misplaced elements and wrong image on inventory page |
| **Severity** | Major |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as visual_user / secret_sauce<br>2. Observe inventory page |
| **Expected** | All elements in correct positions, all images correct |
| **Actual** | Cart icon is misplaced, one product image is wrong |

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
| **Expected** | Products sorted alphabetically A to Z |
| **Actual** | Products remain in original order. No sorting occurs |

---

## BUG-006: error_user — sorting throws error popup

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
| **Actual** | Error popup appears: "Sorting is broken! This error has been reported to Backtrace." No sorting occurs |

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

## BUG-008: error_user — add to cart limited to 2 items

| Field | Value |
|-------|-------|
| **ID** | BUG-008 |
| **Title** | Add to Cart button stops working after 2 items for error_user |
| **Severity** | Critical |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as error_user / secret_sauce<br>2. Add first item to cart<br>3. Add second item to cart<br>4. Try to add third item |
| **Expected** | All 6 items can be added to cart |
| **Actual** | Only 2 items can be added. Button stops responding after 2 items |

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
| **Steps** | 1. Login as visual_user / secret_sauce<br>2. Add item to cart<br>3. Go to cart page<br>4. Observe Checkout button position |
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
| **Actual** | Zip/Postal Code field completely missing from form |

---

## BUG-011: problem_user — Last Name field frozen on checkout

| Field | Value |
|-------|-------|
| **ID** | BUG-011 |
| **Title** | Last Name field does not accept input for problem_user |
| **Severity** | Critical |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as problem_user / secret_sauce<br>2. Add item to cart<br>3. Go to checkout<br>4. Click Last Name field<br>5. Try to type any text |
| **Expected** | Last Name field accepts text input normally |
| **Actual** | Field is frozen — no input accepted. Error: "Last Name is required" appears even when attempting to type |

---

## BUG-012: error_user — Last Name field does nothing on checkout

| Field | Value |
|-------|-------|
| **ID** | BUG-012 |
| **Title** | Last Name field does nothing when clicked for error_user |
| **Severity** | Critical |
| **Priority** | High |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as error_user / secret_sauce<br>2. Add item to cart<br>3. Go to checkout<br>4. Click Last Name field<br>5. Try to type any text |
| **Expected** | Last Name field accepts text input normally |
| **Actual** | Nothing happens when clicking the field. No input possible |

---

## BUG-013: standard_user — checkout allowed with empty cart

| Field | Value |
|-------|-------|
| **ID** | BUG-013 |
| **Title** | User can proceed to checkout with empty cart |
| **Severity** | Minor |
| **Priority** | Medium |
| **Status** | Open |
| **Environment** | Chrome, Windows |
| **Steps** | 1. Login as standard_user / secret_sauce<br>2. Do not add any items to cart<br>3. Click cart icon<br>4. Click Checkout button |
| **Expected** | Warning message: "Cart is empty" OR Checkout button disabled |
| **Actual** | User proceeds to checkout with empty cart. No warning shown |
