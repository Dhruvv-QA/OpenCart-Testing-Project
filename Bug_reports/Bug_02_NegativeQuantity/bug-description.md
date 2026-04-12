# Negative quantity shows success but product not added

## Description
When a user enters a negative quantity (e.g., -1) and clicks on "Add to Cart", the system displays a success message indicating the product has been added. However, the cart remains empty.

## Steps to Reproduce
1. Open any product page
2. Enter quantity as -1
3. Click on "Add to Cart"

## Actual Result
Success message is displayed but product is not added to cart.

## Expected Result
System should not accept negative quantity and should display an error message.

## Severity
High

## Priority
High

## Impact
User receives misleading feedback, which can reduce trust and cause confusion.
