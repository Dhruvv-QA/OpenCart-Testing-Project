# Product comparison page not accessible via UI navigation

## Description
When a user adds a product to the comparison list, a success message is displayed with a temporary link to access the comparison page. However, the message disappears within a few seconds, and there is no permanent navigation option (header, footer, or menu) to access the comparison page.

## Steps to Reproduce
1. Open any product page
2. Click on "Add to Compare"
3. Observe the success message with comparison link
4. Wait for the message to disappear
5. Try to find the comparison page via UI

## Actual Result
User is unable to access the comparison page after the message disappears. No navigation option is available.

## Expected Result
The comparison page should be accessible through a persistent UI element such as header, footer, or menu.

## Additional Observation
The comparison page exists and can be accessed via direct URL:
index.php?route=product/compare  
However, it is not accessible through UI navigation.

## Severity
High

## Priority
High

## Impact
Users are unable to access and use the product comparison feature, which affects product decision-making and overall user experience.

## Recommendation
Provide a permanent navigation option for product comparison in the UI (header, footer, or menu).
