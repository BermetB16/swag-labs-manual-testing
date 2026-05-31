# swag-labs-manual-testing
# Swag Labs — Manual Testing Portfolio

**Site:** https://www.saucedemo.com/
**Tester:** Bermet Beisheeva
**Date:** May 2026

## Project Overview
Manual functional testing of Swag Labs — 
a demo e-commerce website. 
Covers login, products, cart and checkout modules.

## Test Summary
| Module | Total | Pass | Fail |
|--------|-------|------|------|
| Login | 9 | 5 | 4 |
| Products | 3 | 1 | 2 |
| Cart | 3 | 0 | 3 |
| Checkout | 3 | 0 | 3 |
| **Total** | **18** | **6** | **12** |

## Bugs Found
| ID | Title | Severity |
|----|-------|----------|
| BUG-001 | Slow login for performance_glitch_user | Minor |
| BUG-002 | Wrong product images for problem_user | Major |
| BUG-003 | Remove button not working for error_user | Critical |
| BUG-004 | Visual bugs for visual_user | Major |
| BUG-005 | Sorting not working for problem_user | Major |
| BUG-006 | Sorting error popup for error_user | Critical |
| BUG-007 | Add to cart limited to 2 items for problem_user | Critical |
| BUG-008 | Add to cart limited to 2 items for error_user | Critical |
| BUG-009 | Checkout button misplaced for visual_user | Major |
| BUG-010 | Zip field missing on checkout for visual_user | Critical |
| BUG-011 | Last Name field frozen for problem_user | Critical |
| BUG-012 | Last Name field does nothing for error_user | Critical |
| BUG-013 | Checkout allowed with empty cart | Minor |
## Repository Structure
```
test-cases/
├── TC_LOGIN.md
├── TC_PRODUCTS.md
├── TC_CART.md
└── TC_CHECKOUT.md
bug-reports/
└── BUGS.md
screenshots/
└── (bug screenshots)
```
## Tools Used
- Chrome DevTools
- GitHub
- Markdown

## Author
**Bermet Beisheeva** — Junior QA Engineer
- GitHub: github.com/BermetB16
- LinkedIn: linkedin.com/in/бермет-бейшеева-955275351
