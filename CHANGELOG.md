# Changelog

All notable changes to the **Facebook Enhancer** project will be documented in this file.

## [3.32] - 2025-12-16
### Added
- **Hide Gaming**: New option to hide Facebook Gaming sections in the feed and sidebar links.
- **Hide Reels Tab**: Specific option to hide the "Reels" button in the left sidebar navigation (independent of feed Reels).
- **Hide Create Room**: New filter to remove "Create Room" / Video Chat banners.

### Changed
- **Optimization**: improved the `processMutations` observer to reduce layout thrashing and improve performance during scrolling.
- **Selectors**: Refactored internal selector logic for better maintainability.

## [3.31]
### Changed
- **Performance**: Major overhaul of the observation system (switching to targeted mutation processing).
- **Logic**: Smarter "Force Most Recent" that respects user navigation.
- **Fixes**: Adjustments to right-rail ad blocking and hotkey safety.

## [3.30]
### Added
- Initial "Hide Reels" aggressive heuristics.
- Keyword regex support.

---
*Script author: Eliminater74*
