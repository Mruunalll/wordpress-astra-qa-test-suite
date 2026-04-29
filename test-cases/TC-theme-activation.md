# TC theme activation

| TC ID | Module | Title | Preconditions | Test Steps | Expected Result | Priority | Severity |
|-------|--------|-------|---------------|------------|-----------------|----------|----------|
| TC-001 | Activation | Activate Astra on fresh WP install | WordPress 6.5 installed; no other theme active | 1. Go to Appearance → Themes 2. Search "Astra" 3. Install and Activate | Astra activated; default homepage renders without errors; no PHP warnings | High | Critical |
| TC-002 | Activation | Switch from TwentyTwenty to Astra | TwentyTwenty active with existing posts/pages | 1. Install Astra 2. Click Activate | Astra applied; existing content accessible; no layout broken; no data lost | High | Critical |
| TC-003 | Global | Change global font family | Astra active | 1. Customizer → Global → Typography 2. Set Body Font to "Lato" 3. Publish | Lato font loaded on all pages; Google Fonts request visible in DevTools network tab | High | Major |
| TC-004 | Global | Set font size out of recommended range | Customizer open | 1. Set Body Font Size to 100px 2. Publish | Text displays at 100px; no crash; layout may break (acceptable) — no JS errors | Medium | Minor |
| TC-005 | Global | Set invalid hex color | Global → Colors | 1. Click Primary Color 2. Type "GGGGGG" in hex field | Field rejects input or reverts to previous valid value; no broken colour applied | Medium | Major |
| TC-006 | Global | Reset all customizer settings | Customizations made | 1. Customizer → Astra Options 2. Click "Reset All Settings" button 3. Confirm | All settings revert to Astra defaults; no partial reset state | Medium | Major |
