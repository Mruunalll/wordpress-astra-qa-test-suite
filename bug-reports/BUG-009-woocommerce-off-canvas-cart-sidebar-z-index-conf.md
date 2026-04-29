## BUG-009 — WooCommerce off-canvas cart sidebar z-index conflicts with sticky header

**Title:** WooCommerce off-canvas cart sidebar z-index conflicts with sticky header
**Environment:** Chrome 124, WooCommerce 8.3, Astra 4.6
**Severity:** Minor | **Priority:** Medium

**Steps to Reproduce:**
1. Enable Sticky Header
2. Enable Off-Canvas Cart (Astra WooCommerce settings)
3. Add product to cart
4. Click cart icon to open off-canvas sidebar

**Expected Result:** Off-canvas sidebar slides in above all content including sticky header
**Actual Result:** Sticky header renders above the off-canvas cart overlay — cart partially obscured by the header bar

---
