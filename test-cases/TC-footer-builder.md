# TC footer builder

| TC ID | Module | Title | Preconditions | Test Steps | Expected Result | Priority | Severity |
|-------|--------|-------|---------------|------------|-----------------|----------|----------|
| TC-013 | Footer | Set 3-column footer layout | Footer Builder active | 1. Footer → Columns → Select 3-column 2. Add widget to each column 3. Publish | Three-column layout renders on desktop; stacks to 1 column on mobile | Medium | Major |
| TC-014 | Footer | Add dynamic copyright year | Footer Builder | 1. Add text widget 2. Enter `© [current_year] My Brand` 3. Publish | Current year displays dynamically; not hardcoded | Low | Minor |
| TC-015 | Footer | Hide footer on specific page | Footer visible globally | 1. Edit a specific page 2. Astra Page Settings → Disable Footer 3. Update | Footer hidden only on that page; visible on all others | Medium | Minor |
