# GroceryMate - Test Case Design

## Feature 1: Advanced Product Search & Filtering

### Test Case 1.1
**Title:** Search by product name returns correct results  
**Technique:** Equivalence Partitioning  
**Steps:**
1. Go to search bar.
2. Enter "Milk".
3. Click search.  
**Expected Result:** All returned products contain the word "Milk".

### Test Case 1.2
**Title:** Filter products by price range  
**Technique:** Boundary Value Analysis  
**Steps:**
1. Open filter menu.
2. Set price range: $5 - $10.
3. Apply filter.  
**Expected Result:** All products are priced between $5 and $10.

### Test Case 1.3
**Title:** Filter by stock availability  
**Technique:** Equivalence Partitioning  
**Steps:**
1. Open filter menu.
2. Select "In Stock".
3. Apply filter.  
**Expected Result:** All products displayed are in stock.

---
## Feature 2: Cart Update Functionality

### Test Case 2.1
**Title:** Update product quantity in cart  
**Technique:** State Transition Testing  
**Steps:**
1. Add a product to cart.
2. Change quantity from 1 to 3.
3. Verify total price update.  
**Expected Result:** Total price matches 3 × unit price.

### Test Case 2.2
**Title:** Remove product from cart  
**Technique:** State Transition Testing  
**Steps:**
1. Add a product to cart.
2. Click remove button.
3. Verify product disappears.  
**Expected Result:** Product is removed and total price updates accordingly.

### Test Case 2.3
**Title:** Auto price update without page refresh  
**Technique:** Decision Table Testing  
**Steps:**
1. Add a product to cart.
2. Change quantity.
3. Observe price change.  
**Expected Result:** Price updates instantly without page reload.

---
## Feature 3: One-Click Checkout

### Test Case 3.1
**Title:** Checkout with saved card and address  
**Technique:** Happy Path Testing  
**Steps:**
1. Ensure user has saved payment details.
2. Click "One-Click Checkout".  
**Expected Result:** Order completes successfully.

### Test Case 3.2
**Title:** Checkout fails without saved payment method  
**Technique:** Negative Testing  
**Steps:**
1. Remove saved payment method from account.
2. Click "One-Click Checkout".  
**Expected Result:** User sees error message prompting to add payment.

### Test Case 3.3
**Title:** Verify order confirmation email is sent  
**Technique:** State Transition Testing  
**Steps:**
1. Complete checkout with one-click.
2. Check email inbox.  
**Expected Result:** Order confirmation email is received.

---
## Automation Candidates
- Feature 1.1 (Search by product name)
- Feature 2.1 (Update product quantity in cart)
- Feature 3.1 (Checkout with saved card and address)

Reason: These are frequently executed test cases and benefit from automation for regression purposes.
