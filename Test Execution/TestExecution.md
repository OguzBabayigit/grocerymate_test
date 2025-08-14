# GroceryMate - Test Execution Report

**Date:** 2025-08-14  
**Tester:** Oğuz  
**Environment:** Staging - https://grocerymate.masterschool.com/  
**Browser:** Chrome 115 / Windows 11

| Test Case ID | Feature | Description | Result | Notes |
|--------------|---------|-------------|--------|-------|
| TC-1.1 | Search & Filtering | Search by product name returns correct results | PASS | Results matched search term |
| TC-1.2 | Search & Filtering | Filter products by price range | FAIL | Returned a product priced outside the range |
| TC-1.3 | Search & Filtering | Filter by stock availability | PASS | Only in-stock products shown |
| TC-2.1 | Cart Update | Update product quantity in cart | PASS | Price updated correctly |
| TC-2.2 | Cart Update | Remove product from cart | FAIL | Cart total did not update immediately |
| TC-2.3 | Cart Update | Auto price update without page refresh | PASS | Price updated instantly |
| TC-3.1 | One-Click Checkout | Checkout with saved card and address | PASS | Order placed successfully |
| TC-3.2 | One-Click Checkout | Checkout fails without saved payment method | FAIL | System proceeded to checkout without payment |
| TC-3.3 | One-Click Checkout | Verify order confirmation email is sent | PASS | Email received |

## Additional Test Cases Found During Execution
**TC-4.1:** Validate search with special characters → PASS  
**TC-4.2:** Verify cart supports more than 50 items → PASS
