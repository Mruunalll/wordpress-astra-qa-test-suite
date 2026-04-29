# TC mobile responsive

| TC ID | Module | Title | Preconditions | Test Steps | Expected Result | Priority | Severity |
|-------|--------|-------|---------------|------------|-----------------|----------|----------|
| TC-028 | Typography | Line height boundary — min value | Customizer → Typography | 1. Set Body Line Height to 0 | Input rejects 0 or reverts to minimum (e.g., 1.0); no text overlap | Medium | Major |
| TC-029 | Mobile | Customizer mobile preview vs real device | Customizer open | 1. Switch to mobile preview in customizer 2. Compare with iPhone 14 Safari on same URL | Mobile preview and real device within 10% visual match; no gross differences | High | Major |
| TC-030 | Child Theme | Child theme styles not overridden by Astra update | Child theme with custom CSS | 1. Activate child theme 2. Add custom CSS 3. Update Astra to latest version | Custom CSS in child theme preserved after update | High | Critical |
