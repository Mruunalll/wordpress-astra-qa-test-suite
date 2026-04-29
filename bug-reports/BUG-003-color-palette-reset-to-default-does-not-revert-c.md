## BUG-003 — Color palette "Reset to Default" does not revert child theme CSS variable overrides

**Title:** Color palette "Reset to Default" does not revert child theme CSS variable overrides
**Environment:** WordPress 6.5, Astra with active child theme
**Severity:** Major | **Priority:** Medium

**Steps to Reproduce:**
1. Activate Astra child theme with `--ast-global-color-0` set to `#FF0000` in child style.css
2. In Customizer, change Primary Color to `#0000FF`
3. Publish
4. Click "Reset All Settings"

**Expected Result:** Color resets to Astra default (not child theme value)
**Actual Result:** Color visually reverts to child theme red (#FF0000), not to Astra default — confusing which value is "default"

---
