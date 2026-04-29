# Requirements Traceability Matrix

## RTM

| Requirement ID | Requirement Description | Test Case IDs | Status |
|----------------|------------------------|---------------|--------|
| REQ-001 | Astra activates without errors on WP 6.5 | TC-001, TC-002 | ✅ Pass |
| REQ-002 | Global typography controls work correctly | TC-003, TC-004, TC-028 | ⚠️ Partial (BUG letter-spacing) |
| REQ-003 | Color palette accepts valid hex values | TC-005 | ✅ Pass |
| REQ-004 | Settings can be fully reset | TC-006 | ❌ Fail (BUG-003) |
| REQ-005 | Custom logo upload and sizing works | TC-007, TC-008 | ❌ Fail (BUG-002) |
| REQ-006 | Sticky header functions on scroll | TC-009 | ❌ Fail (BUG-006 - anchor overlap) |
| REQ-007 | Header CTA button renders and links correctly | TC-010 | ✅ Pass |
| REQ-008 | Transparent header available for homepage | TC-011 | ❌ Fail (BUG-005 - contrast) |
| REQ-009 | Mobile hamburger menu works | TC-012 | ❌ Fail (BUG-008) |
| REQ-010 | Footer layout options (1/2/3 col) work | TC-013 | ✅ Pass |
| REQ-011 | Dynamic year shortcode in footer | TC-014 | ❌ Fail (BUG-010 - child theme) |
| REQ-012 | Footer hideable per page | TC-015 | ✅ Pass |
| REQ-013 | Starter Templates library loads | TC-016 | ✅ Pass |
| REQ-014 | Template preview works | TC-017 | ✅ Pass |
| REQ-015 | Full site import works on clean WP | TC-018 | ✅ Pass |
| REQ-016 | Existing content protected during import | TC-019, TC-020 | ❌ Fail (BUG-001) |
| REQ-017 | Single page import doesn't affect other content | TC-021 | ✅ Pass |
| REQ-018 | Import works with Elementor | TC-022 | ✅ Pass |
| REQ-019 | Partial import leaves site intact | TC-023 | ✅ Pass |
| REQ-020 | Preview matches import | TC-024 | ❌ Fail (BUG-004) |
| REQ-021 | WooCommerce cart icon in header | TC-026 | ❌ Fail (BUG-009 - z-index) |
| REQ-022 | Mobile preview accuracy | TC-029 | ⚠️ Partial |
| REQ-023 | Child theme styles respected | TC-030 | ✅ Pass |

---
