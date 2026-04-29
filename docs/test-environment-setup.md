# Test Environment Setup — LocalWP

## Install LocalWP
1. Download LocalWP from the official site.
2. Create a site with WordPress 6.5, PHP 8.2, and MySQL 8.
3. Install Astra from Appearance → Themes → Add New.
4. Install Starter Templates from Plugins → Add New.

## Two Environments Required
| Environment | Configuration |
|-------------|---------------|
| clean-wp | Fresh WordPress install with no demo content |
| existing-wp | Pre-loaded with 5 posts, 3 pages, and 10 media library images |

## Remote Staging
| Item | Purpose |
|------|---------|
| SiteGround staging | Cross-browser and real-device validation |
| BrowserStack | iOS and Android spot checks |

## Evidence Requirements
Capture before/after screenshots for import-related tests, especially media library and menu/widget changes on the existing-content environment.
