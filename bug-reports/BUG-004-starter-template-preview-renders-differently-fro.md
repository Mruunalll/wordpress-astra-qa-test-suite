## BUG-004 — Starter Template preview renders differently from actual import (3 templates confirmed)

**Title:** Starter Template preview renders differently from actual import (3 templates confirmed)
**Environment:** Chrome 124, Gutenberg builder, Starter Templates 4.3
**Severity:** Major | **Priority:** High

**Affected Templates:** "Brandstore", "Digital Agency", "Yoga Studio"

**Steps to Reproduce:**
1. Open Starter Templates library
2. Click "Brandstore" template
3. View full-screen preview — note hero section font and button color
4. Import template
5. Visit homepage

**Expected Result:** Imported site matches preview screenshot
**Actual Result:**
- Hero font weight is Regular in import vs Bold in preview
- CTA button colour is grey in import vs orange in preview
- Section spacing differs significantly

---
