## BUG-001 — Full site import deletes existing media library items without warning

**Title:** Full site import deletes existing media library items without warning
**Environment:** Chrome 124, WordPress 6.5, Astra 4.6, Starter Templates 4.3, LocalWP
**Severity:** Critical | **Priority:** High

**Steps to Reproduce:**
1. Install WordPress with 10 custom images uploaded to Media Library
2. Install Starter Templates
3. Choose any full-site template
4. Click "Import Complete Site" and confirm
5. After import completes, go to Media Library

**Expected Result:** Existing 10 images preserved; template images added alongside them
**Actual Result:** All 10 existing images deleted; only template demo images remain in Media Library

---
