## BUG-002 — Header Builder drops custom logo when switching between mobile and desktop breakpoints in Customizer

**Title:** Header Builder drops custom logo when switching between mobile and desktop breakpoints in Customizer
**Environment:** Chrome 124, macOS Sonoma, Astra 4.6
**Severity:** Major | **Priority:** High

**Steps to Reproduce:**
1. Upload custom logo in Customizer → Header
2. Publish
3. In Customizer, click mobile preview icon
4. Click back to desktop preview icon
5. Observe logo in header

**Expected Result:** Logo persists in both desktop and mobile previews
**Actual Result:** Logo disappears from header preview after toggling back to desktop view; only visible after refreshing customizer

---
