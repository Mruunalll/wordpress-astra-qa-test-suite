# TC header builder

| TC ID | Module | Title | Preconditions | Test Steps | Expected Result | Priority | Severity |
|-------|--------|-------|---------------|------------|-----------------|----------|----------|
| TC-007 | Header | Upload custom logo | Customizer → Header → Logo | 1. Click Change Logo 2. Upload 200×60px PNG 3. Publish | Logo displays in header at correct size; Retina 2× not broken | High | Major |
| TC-008 | Header | Set logo max-width | Logo uploaded | 1. Set Logo Max Width to 80px 2. Publish | Logo scales to 80px width; proportions maintained | Medium | Minor |
| TC-009 | Header | Enable sticky header | Customizer → Header → Sticky | 1. Toggle Sticky Header ON 2. Publish 3. Open site 4. Scroll down | Header stays fixed at top; does not flicker or overlap content on scroll | High | Major |
| TC-010 | Header | Add CTA button to header | Header Builder active | 1. Drag Button widget to header row 2. Set text "Get Started" and URL "/" 3. Publish | Button appears in header; clicks correctly; styled per theme colors | High | Major |
| TC-011 | Header | Switch to transparent header | Homepage with hero section | 1. Enable Transparent Header for front page 2. Publish | Header overlays hero image; logo/menu still visible; no readability issues | Medium | Major |
| TC-012 | Header | Mobile header hamburger | Mobile preview / real device | 1. Open site on mobile 2. Tap hamburger icon | Mobile nav opens; all menu items accessible; close (×) works | High | Critical |
