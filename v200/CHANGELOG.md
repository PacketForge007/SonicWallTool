# Changelog

All notable changes to this project will be documented in this file.

The format is inspired by Keep a Changelog and follows Semantic Versioning (MAJOR.MINOR.PATCH).

---

## [2.0.0] - 2026-07-05

### 🚀 Major Release

This release represents a significant upgrade to SonicWallTool, introducing a redesigned user interface, reusable GUI components, enhanced file management, and a powerful log search engine.

### ✨ Added

#### General
- Unified common GUI layout shared across all generator tabs.
- Improved application responsiveness and usability.
- Window size persistence between sessions.
- Enhanced drag-and-drop support for importing files.

#### Treeview Engine
- Multi-file import support.
- File count display.
- Remove selected files.
- Clear all imported files.
- Keyboard shortcut support.
- Improved Treeview selection handling.
- Shared Treeview engine across all generator tabs.

#### Log Search v2
- Live search while typing.
- Highlight all matching results.
- Highlight current match.
- Match counter (Current / Total).
- Previous / Next navigation.
- Wrap-around navigation.
- Automatic scrolling to current match.
- Independent search state for every tab.
- Keyboard shortcuts:
  - Ctrl + F → Focus search box
  - Enter → Next match
  - Shift + Enter → Previous match
  - F3 → Next match
  - Shift + F3 → Previous match

### 🔄 Improved

- Shared GUI architecture to reduce duplicate code.
- Improved layout consistency across all tabs.
- Better Treeview usability.
- Improved log viewing experience.
- Cleaner and more maintainable internal code structure.

### 🐞 Fixed

- Numerous Treeview selection issues.
- Log search navigation consistency.
- Search state isolation between tabs.
- Various GUI layout and usability improvements.
- General bug fixes and stability enhancements.

---

## [1.0.0]

Initial public release.

Features included:
- Local User Generator
- Address Object Generator
- Service Object Generator
- User Group Generator
- DHCP Static Reservation Generator