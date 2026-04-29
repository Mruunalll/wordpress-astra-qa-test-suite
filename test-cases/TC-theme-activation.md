# TC theme activation

| TC ID | Module | Title | Preconditions | Test Steps | Expected Result | Priority | Severity |
|-------|--------|-------|---------------|------------|-----------------|----------|----------|
| TC-003 | Global | Change global font family | Astra active | 1. Customizer → Global → Typography 2. Set Body Font to "Lato" 3. Publish | Lato font loaded on all pages; Google Fonts request visible in DevTools network tab | High | Major |
| TC-004 | Global | Set font size out of recommended range | Customizer open | 1. Set Body Font Size to 100px 2. Publish | Text displays at 100px; no crash; layout may break (acceptable) — no JS errors | Medium | Minor |
| TC-005 | Global | Set invalid hex color | Global → Colors | 1. Click Primary Color 2. Type "GGGGGG" in hex field | Field rejects input or reverts to previous valid value; no broken colour applied | Medium | Major |
| TC-006 | Global | Reset all customizer settings | Customizations made | 1. Customizer → Astra Options 2. Click "Reset All Settings" button 3. Confirm | All settings revert to Astra defaults; no partial reset state | Medium | Major |
| TC-030 | Child Theme | Child theme styles not overridden by Astra update | Child theme with custom CSS | 1. Activate child theme 2. Add custom CSS 3. Update Astra to latest version | Custom CSS in child theme preserved after update | High | Critical |
