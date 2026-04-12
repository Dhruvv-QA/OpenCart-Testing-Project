# Out of stock product can be added to cart

## Description
User is able to add a product to the cart even when the product is marked as "Out of Stock".

## Steps to Reproduce
1. Open a product which is marked as "Out of Stock"
2. Click on "Add to Cart"

## Actual Result
Product gets added to cart successfully and success message is displayed.

## Expected Result
System should restrict adding the product to cart and display appropriate message like "Out of Stock".

## Severity
High

## Priority
High

## Impact
Users may proceed with unavailable products which leads to poor user experience and order failure.

## Recommendation
Disable "Add to Cart" button or restrict action when product is out of stock.
