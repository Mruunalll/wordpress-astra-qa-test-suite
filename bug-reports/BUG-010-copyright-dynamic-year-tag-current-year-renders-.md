## BUG-010 — Copyright dynamic year tag `[current_year]` renders as plain text on child themes

**Title:** Copyright dynamic year tag `[current_year]` renders as plain text on child themes
**Environment:** WordPress 6.5, Astra Child Theme active
**Severity:** Minor | **Priority:** Low

**Steps to Reproduce:**
1. Activate Astra child theme
2. Footer Builder → Add text widget → Enter `© [current_year] Brand`
3. Publish
4. View footer on frontend

**Expected Result:** `[current_year]` replaced with current year (e.g., 2026)
**Actual Result:** Footer shows literally `© [current_year] Brand` — shortcode not processed in child theme context

---
