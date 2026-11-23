# Changelog

All notable changes to this project are documented in this file.

Format: [Keep a Changelog](https://keepachangelog.com/en/1.1.0/)
Versioning: [Semantic Versioning](https://semver.org/)

> No version has been tagged yet. The entries below summarize the git history up to the first release.

---

## [Unreleased]

### Added
- Svelte app that simulates one month of food costs for eating out, bento and home cooking.
- Quick simulation screen and an always-visible summary bar.
- Monthly living cost simulation with rent, utilities and telecom costs.
- Switchable source for food costs (calendar or quick simulation).
- Month selector with previous/next navigation; state is kept per month.
- State is saved in `localStorage` (calendar, quick simulation, living cost settings).
- Prices updated to 2026 levels; drink items added.
- CSV export with error handling, validation and a date in the file name (#3).
- Vitest and Testing Library setup (#2).
- Static deployment to GitHub Pages.

### Fixed
- Svelte plugin configuration in `vite.config.js`.
- CI: reusable workflow pins point at commits reachable from the qa-workflows default branch (#13).
