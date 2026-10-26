# Changelog

All notable changes to Codex Workspace Manager are documented here.

## [0.7.3] - 2026-10-25

- Declared the official OpenAI Codex extension (`openai.chatgpt`) as an extension dependency so VS Code can install it automatically.
- Kept the terminal and read-only fallbacks for environments where the official extension is unavailable or cannot activate.

## [0.7.2] - 2026-10-25

- Switched the default user interface, settings, commands, and documentation to English for Marketplace distribution.
- Updated the publisher metadata to `diginperu` and added the Marketplace publishing command.

## [0.7.1] - 2026-10-25

- Added this changelog.
- Added anonymized reference screenshots for the sessions view and settings view.
- Kept screenshots free of real session names, IDs, local paths, private messages, and developer project names.
- Prepared the Marketplace PNG icon and improved the monochrome sidebar glyph.

## [0.7.0] - 2026-10-25

- Added automated visual-opening tests for ID validation, tab reuse, concurrent-open deduplication, and safe fallback propagation.
- Kept the official-extension integration as a manual integration test because its visual route is not a stable public API.

## [0.6.2] - 2026-10-25

- Hid internal route details from the settings screen.
- Simplified the user-facing explanation: visual chat first, terminal fallback second.

## [0.6.1] - 2026-10-25

- Documented the internal route limitation used for visual chat opening.
- Added the fallback chain: visual chat, `codex resume`, and read-only JSONL.

## [0.6.0] - 2026-10-25

- Added a direct shortcut to a filtered settings screen.
- Improved descriptions for all extension options.

## [0.5.0] - 2026-10-25

- Added favorite or pinned sessions.
- Pinned sessions appear first and persist between restarts.

## [0.4.0] - 2026-10-25

- Added visual opening of the original chat when the official extension is available.
- Added automatic opening of the most recent session when VS Code starts.
- Added a safe terminal fallback and read-only JSONL view.

## [0.3.0] - 2026-10-25

- Added workspace filtering, search, sorting, and multi-root support.
- Added reliable refresh when workspace folders change.

## [0.2.0] - 2026-10-25

- Added a TreeView for local Codex sessions.
- Added a bounded-read JSONL parser and read-only view.

## [0.1.0] - 2026-10-25

- Initial MVP release.
