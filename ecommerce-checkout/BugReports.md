# Bug Reports – Checkout

## Bug ID: BUG_CHK_001
- **Title:** Checkout allows payment submission with empty address fields
- **Severity:** High
- **Priority:** High
- **Environment:** Chrome, Windows 10

### Steps to Reproduce
1. Add product to cart
2. Proceed to checkout
3. Leave shipping address empty
4. Submit payment

### Expected Result
User should be prompted to complete mandatory address fields.

### Actual Result
Payment submission proceeds without validation.

### Status
Open
