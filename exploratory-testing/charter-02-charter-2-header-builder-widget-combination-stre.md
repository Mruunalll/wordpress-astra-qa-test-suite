# Charter 2: Header Builder — Widget Combination Stress Test
**Mission:** Find layout breakages and logic conflicts between header builder widgets
**Area:** Astra Header Builder
**Duration:** 60 minutes

**Session Notes:**
- Row 1: Logo + Nav + Search + Button — all 4 working on desktop ✅
- Row 1 + Row 2 stacked — second row disappears on tablet ⚠️
- Search overlay opens correctly ✅; but pressing ESC doesn't close it ❌
- Transparent header + dark background section: heading text invisible (BUG-005) ❌
- Added 3 buttons to header — layout overflows on 1366px viewport ❌
- HTML widget in header accepts raw `<script>` — executes (security note — expected for admin use only) ⚠️

**Edge Cases Found:**
- Header with 5+ navigation items wraps onto 2 lines at 1280px — no ellipsis/overflow handling
- Logo alt text blank when logo set via Customizer — accessibility issue

---
