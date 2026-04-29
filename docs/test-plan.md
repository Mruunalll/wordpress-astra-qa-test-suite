# Test Plan

## Project Overview

### Application Description
Astra is one of the most popular WordPress themes (2M+ active installs). It ships with a companion plugin — **Starter Templates** — that provides 200+ pre-built website templates importable in one click. Together, they allow users to build full websites with WooCommerce, Elementor, Gutenberg, or Beaver Builder without writing code. This QA project covers theme customizer settings, header/footer builder, starter template import flow, and WooCommerce integration.

### Scope

#### ✅ In-Scope
- Astra theme activation and customizer (Global Settings, Header, Footer, Blog, WooCommerce)
- Header Builder: logo, menu, search, button widgets
- Footer Builder: copyright, widgets, footer bar
- Starter Templates plugin: browse, preview, import (full site + single page)
- Typography and color palette controls
- WooCommerce integration settings (product cards, cart icon in header)
- Responsive/mobile preview in customizer
- Cross-browser rendering validation
- Child theme compatibility (basic)

#### ❌ Out-of-Scope
- Astra Pro premium features (unless free tier covers them)
- Page builder internals (Elementor / Beaver Builder themselves)
- WordPress core bugs
- Plugin conflicts with non-bundled plugins
- Performance benchmarking

### Test Environment

| Category | Details |
|----------|---------|
| WordPress | 6.5 (clean install + existing-content install) |
| Astra Version | 4.6.x (free) |
| Starter Templates | 4.3.x |
| Browsers | Chrome 124, Firefox 125, Safari 17, Edge 124 |
| OS | Windows 11, macOS Sonoma |
| Mobile | iPhone 14 (iOS 17), Samsung Galaxy S23 (Android 14) |
| Server | Local: LocalWP 8.x | Staging: SiteGround staging |
| Page Builders | Gutenberg (default), Elementor Free |
| PHP | 8.2 |

---

## Test Strategy

### Testing Types

| Type | Description |
|------|-------------|
| **Functional** | All customizer controls, import flow, and builder options work as designed |
| **Regression** | Key flows re-tested after theme or plugin update |
| **Exploratory** | Unscripted sessions: import on non-clean sites, edge-case customizer combos |
| **Usability** | Customizer workflow, import wizard, preview accuracy |
| **Compatibility** | Cross-browser, cross-page-builder, child theme |
| **Boundary** | Max/min font sizes, color contrast edge cases, max columns in layouts |
| **Negative** | Import with broken connection, activate without WordPress minimum version, invalid hex color inputs |

### Approach
1. Set up two WordPress environments: **clean install** and **existing-content install**
2. Activate Astra; run customizer test cases systematically per section
3. Install Starter Templates plugin; test import flow on both environments
4. Execute cross-browser visual checks using screenshots + diff comparison
5. Run exploratory sessions (documented via charters)
6. Log defects with annotated screenshots, env details, and repro steps

### Risk Areas & Mitigation

| Risk | Likelihood | Mitigation |
|------|-----------|------------|
| Full-site import destroys existing content | High | Test on existing-content install specifically; document warnings |
| Mobile breakpoint rendering varies per browser | High | Test on real devices + DevTools |
| Customizer preview ≠ frontend output | Medium | Cross-check every setting on live site URL |
| Template import fails on slow connections | Medium | Throttle to "Slow 3G" in DevTools; test partial import states |
| Child theme overrides not respected | Medium | Basic child theme activation + style override test |
| Elementor vs Gutenberg template behaviour differs | Medium | Test import with both builders enabled |

---
