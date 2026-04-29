## BUG-007 — Import progress bar freezes at 67% then jumps to 100% (no intermediate feedback)

**Title:** Import progress bar freezes at 67% then jumps to 100% (no intermediate feedback)
**Environment:** Chrome 124, Slow 3G throttling, Starter Templates 4.3
**Severity:** Minor | **Priority:** Low

**Steps to Reproduce:**
1. Open DevTools → Network → set to "Slow 3G"
2. Start full site import
3. Observe progress bar

**Expected Result:** Smooth progress bar increments; or clear stage labels ("Importing pages...", "Importing media...")
**Actual Result:** Progress bar moves to 67%, freezes for 45+ seconds, then jumps to 100%

---
