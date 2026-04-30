# 🎨 WordPress Astra Theme — Manual QA Test Suite
### Astra Theme 4.x + Starter Templates Plugin — Test Plan, Scenarios, Test Cases, Defects, RTM

[![Test Cases](https://img.shields.io/badge/Test%20Cases-30-blue)]()
[![Bugs Found](https://img.shields.io/badge/Bugs%20Found-10-red)]()
[![Pass Rate](https://img.shields.io/badge/Pass%20Rate-56.7%25-orange)]()
[![Platform](https://img.shields.io/badge/Platform-WordPress%206.5-green)]()

## 📌 Project Summary
Executed end-to-end manual QA on the Astra WordPress theme and Starter Templates plugin and documented the complete QA artifact set: test plan, high-level scenarios, manual test cases, defect reports, exploratory charters, requirements traceability matrix, and final test summary report. Testing used both clean WordPress and existing-content environments to expose real-world data integrity risk.

## 🎯 What Was Tested
| Module | Test Cases | Bugs Found |
|--------|-----------:|-----------:|
| Theme Activation / Global Settings | 6 | 1 |
| Header Builder | 6 | 3 |
| Footer Builder | 3 | 1 |
| Starter Templates Import | 10 | 4 |
| WooCommerce Integration | 2 | 1 |
| Typography Boundary | 1 | 0 |
| Mobile / Child Theme Regression | 2 | 0 |

## 🔴 Critical Defects Identified
| ID | Title | Severity |
|----|-------|----------|
| BUG-001 | Full-site import overwrites existing media library without warning | Critical |
| BUG-008 | Mobile menu remains open after anchor link tap | Critical |

## 🧪 Testing Types Applied
- Functional Testing
- Data Integrity Testing
- Usability Testing
- Boundary Value Analysis
- Cross-browser Compatibility
- Responsive / Mobile Testing
- Regression Testing for child-theme compatibility

## ⚠️ Critical Finding
Starter Templates full-site import on an existing WordPress site can overwrite existing media/content without a sufficient warning or backup prompt. This is treated as a data-loss risk and documented with before/after evidence expectations.

## 📁 Repository Structure
- `/docs` — Test plan, LocalWP setup, and QA checklist
- `/test-cases` — Manual test cases grouped by module
- `/bug-reports` — Individual defect reports plus master bug log
- `/exploratory-testing` — SBTM-style exploratory charters
- `/rtm` — Requirements Traceability Matrix
- `/test-reports` — Final execution summary

## 🛠 Tools Used
| Tool | Purpose |
|------|---------|
| LocalWP | Local WordPress test environments |
| Chrome DevTools | DOM inspection and responsive testing |
| SiteGround Staging | Remote staging validation |
| Loom | Screen recording for defect evidence |
| Lighthouse | Manual performance and Core Web Vitals audit |

## 🔗 See Also
- [E-Commerce QA Suite](https://github.com/Mruunalll/ecommerce-manual-qa-test-suite)
- [AI Application QA Suite](https://github.com/Mruunalll/ai-application-qa-test-suite)
- [SureForms Plugin QA + Automation](https://github.com/Mruunalll/SureForms-Plugin-Test-Suite-Manual-Automation)

## 👤 Author
**Mrunal** | Manual QA Engineer | [GitHub](https://github.com/Mruunalll)
