# GroceryMate - Test Plan

## 1. Analyze the Product
GroceryMate is an online grocery webshop. The new features to be tested are:
1. Advanced Product Search & Filtering (category, price range, stock availability).
2. Cart Update Functionality (update quantity, remove item, auto price update).
3. One-Click Checkout (use saved address and card).

## 2. Design the Test Strategy
Testing will be manual for initial verification, with selected test cases automated using Selenium/Pytest for regression. Testing will be black-box, functional, and UI-focused.

## 3. Define Test Objectives
- Ensure advanced search returns correct and filtered results.
- Validate cart updates in real-time with correct price changes.
- Verify one-click checkout completes successfully without errors.

## 4. Define Test Criteria
**Entry Criteria:**
- Features developed and deployed to staging environment.
- Test data prepared.

**Exit Criteria:**
- All planned test cases executed.
- Critical defects resolved.

## 5. Resource Planning
- 1 QA Engineer (Manual + Automation)
- 1 Developer for bug fixes
- Test tools: Selenium, Pytest, Jira

## 6. Plan Test Environment
- Staging environment: https://staging.grocerymate.masterschool.com/
- Test accounts with sample payment data.

## 7. Schedule & Estimation
- Test case design: 1 day
- Test execution: 2 days
- Automation: 2 days

## 8. Determine Test Deliverables
- Test Plan document
- Test Case document
- Bug reports in Jira
- Automation scripts
