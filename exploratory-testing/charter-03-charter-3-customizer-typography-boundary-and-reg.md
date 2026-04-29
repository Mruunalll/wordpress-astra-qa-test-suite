# Charter 3: Customizer Typography — Boundary and Regression
**Mission:** Test typography inputs at limits and verify live preview accuracy
**Area:** Customizer → Global → Typography
**Duration:** 45 minutes

**Session Notes:**
- Font size 1px: applied, text invisible but no error ⚠️
- Font size 200px: applied, layout breaks acceptably — no crash ✅
- Line height 0: reverts to 1 automatically ✅
- Letter spacing -100px: applied — text invisible ⚠️ (no validation)
- Switching Google Font family: FOUC (flash of unstyled content) in customizer preview for ~1.5 seconds ⚠️
- Custom font via URL (not Google Fonts) not supported in free version — no error shown, silently ignored ❌

**Observations:**
- No input validation on letter-spacing; negative extremes cause invisible text with no feedback
- Live preview occasionally desyncs from actual publish — refresh required to verify

---
