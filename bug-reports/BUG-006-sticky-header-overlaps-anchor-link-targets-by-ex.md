## BUG-006 — Sticky header overlaps anchor-link targets by exactly the header height

**Title:** Sticky header overlaps anchor-link targets by exactly the header height
**Environment:** Chrome 124, Firefox 125 — all devices
**Severity:** Major | **Priority:** Medium

**Steps to Reproduce:**
1. Enable sticky header (height ~70px)
2. Create a page with anchor links (e.g., `#section2`)
3. Click anchor link

**Expected Result:** Target section visible below sticky header with correct scroll offset
**Actual Result:** Sticky header covers the top 70px of the target section — heading of each section hidden behind header

---
