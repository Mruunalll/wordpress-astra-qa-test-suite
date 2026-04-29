# Charter 1: Starter Templates Import on Existing Content Site
**Mission:** Discover data integrity issues when importing templates on a non-clean WordPress install
**Area:** Starter Templates → Import flow on existing-content site
**Duration:** 90 minutes

**Session Notes:**
- Existing posts: survived full import ✅
- Existing pages: 2 of 3 survived; 1 with matching slug got overwritten by template page ❌
- Existing menus: replaced by template menu without warning ❌
- Existing widgets: cleared completely ❌
- Media library: existing images deleted (BUG-001) ❌
- Existing plugins: all remained active ✅
- Partial import of single page: safe — no other content touched ✅

**Observations & Edge Cases:**
- Page with slug `/about` overwritten if template also has `/about` page — no merge option
- Users with existing sites MUST be warned before import; current warning is too subtle (small checkbox UI)

---
