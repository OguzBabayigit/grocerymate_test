# GroceryMate - Bug Reports

## Bug #1 - Price Filter Returning Incorrect Results
**Priority:** High  
**Reporter:** Oğuz  
**Date:** 2025-08-14  
**Environment:** Staging  
**Application:** GroceryMate  
**Page:** Search Results  
**Browser/OS:** Chrome 115 / Windows 11

**Repro Steps:**
1. Go to search bar and search "Bread".
2. Apply price filter $5-$10.
3. Observe results.

**Expected Result:** All products priced between $5 and $10.  
**Actual Result:** One product priced $4.50 is displayed.

---

## Bug #2 - Cart Total Not Updating After Removing Item
**Priority:** Medium  
**Reporter:** Oğuz  
**Date:** 2025-08-14  
**Environment:** Staging  
**Application:** GroceryMate  
**Page:** Cart  
**Browser/OS:** Chrome 115 / Windows 11

**Repro Steps:**
1. Add a product to cart.
2. Add a second product.
3. Remove the first product.

**Expected Result:** Cart total updates immediately.  
**Actual Result:** Total remains the same until page refresh.

---

## Bug #3 - One-Click Checkout Without Payment Method
**Priority:** Critical  
**Reporter:** Oğuz  
**Date:** 2025-08-14  
**Environment:** Staging  
**Application:** GroceryMate  
**Page:** Checkout  
**Browser/OS:** Chrome 115 / Windows 11

**Repro Steps:**
1. Remove all saved payment methods from account.
2. Click "One-Click Checkout".

**Expected Result:** Error message prompting to add payment method.  
**Actual Result:** System proceeds to checkout without payment.
