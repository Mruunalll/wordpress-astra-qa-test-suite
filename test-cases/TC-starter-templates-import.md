# TC starter templates import

| TC ID | Module | Title | Preconditions | Test Steps | Expected Result | Priority | Severity |
|-------|--------|-------|---------------|------------|-----------------|----------|----------|
| TC-016 | Starter Templates | Browse template library | Starter Templates plugin installed and activated | 1. Appearance → Starter Templates 2. Observe library load | All category tabs load; thumbnails display; no broken images; search works | High | Major |
| TC-017 | Starter Templates | Preview template | Library loaded | 1. Click any template thumbnail 2. Click "Preview Full Demo" | Full-screen preview opens; template renders correctly; close button works | High | Major |
| TC-018 | Starter Templates | Import full site — clean WP | Clean WordPress with no posts/pages | 1. Choose template → Click Import 2. Select Gutenberg 3. Click "Import Complete Site" | All pages, images, menus, customizer settings imported; no import errors | High | Critical |
| TC-019 | Starter Templates | Import full site — existing content | WP with 5 posts and 3 pages already created | 1. Import full site template | Warning shown: "Existing content may be affected" before import starts; user must confirm | High | Critical |
| TC-020 | Starter Templates | Import overwrites media library | Existing site with media uploads | 1. Run full site import 2. Check Media Library after | Existing media NOT deleted; new template media added alongside | High | Critical |
| TC-021 | Starter Templates | Import single page | Any existing site | 1. Choose template → Individual Pages → Pick one page 2. Import | Only that single page imported; no other site settings changed; existing pages untouched | High | Major |
| TC-022 | Starter Templates | Import with Elementor builder | Elementor Free installed | 1. Select Elementor as builder 2. Import template | Template renders correctly in Elementor; all sections editable | High | Major |
| TC-023 | Starter Templates | Cancel import mid-way | Import started (first 30%) | 1. Start full site import 2. Click Cancel or close tab at 30% progress | Site remains in pre-import state; no broken pages or half-imported content | Medium | Major |
| TC-024 | Starter Templates | Preview vs actual import mismatch | Library loaded | 1. Preview template 2. Import same template 3. Compare preview vs live | Imported site matches preview within reasonable accuracy (fonts, colors, layout) | High | Major |
| TC-025 | Starter Templates | Re-import different template | First template already imported | 1. Go back to library 2. Select different template 3. Import | New template applied; previous template's customizer settings overwritten cleanly | Medium | Major |
