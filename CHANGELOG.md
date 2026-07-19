# Changelog

All notable public changes to USER_PACKAGE are recorded in this file.

Repository releases follow Semantic Versioning where practical.

## [1.2.0] - Unreleased

### Changed

- Updated `AI_BEHAVIOR_BANK.txt` from version 1.0 to 1.1.
- Added stricter Assistant communication-scope boundaries.
- Added behavior rules preventing unsolicited optional analysis,
  recommendations, alternatives, summaries, conclusions, and future
  discussion after the active communication objective is complete.
- Preserved required communication for blockers, conflicts,
  uncertainties, significant risks, missing information, active
  workflows, and continuity requirements.
- Updated public distribution guidance to prioritize Release packages
  over repository ZIP downloads.

## [1.1.0] - 2026-07-16

### Added

- Public GitHub landing page in `README.md`.
- Public release history in `CHANGELOG.md`.
- Copyright and usage notice in `COPYRIGHT.txt`.
- Public positioning as **An AI Documentation & Collaboration Framework**.
- Repository navigation and quick-start guidance for new readers.
- AI platform compatibility validation documentation.
- Platform-specific usage guidance for supported AI assistants.
- Compatibility records covering ChatGPT, Claude, Copilot, Perplexity,
  and Gemini validation results.

### Changed

- Replaced the internal `README.txt` landing-page role with a GitHub-native `README.md`.
- Clarified the separation between public presentation documents and the plain-text core framework.
- Reframed public documentation around problems, practical value, supported capabilities, and repository navigation.
- Updated USER_PACKAGE initialization guidance from exact response
  matching to behavior-based initialization confirmation.
- Improved cross-platform compatibility documentation to account for
  differences in AI platform capabilities and file handling workflows.
- Clarified the separation of responsibilities between AI_BEHAVIOR_BANK, AI_BEHAVIOR_STANDARD, and AI_OUTPUT_STANDARD through architecture regression and compatibility validation.
- Strengthened deterministic Assistant behavior through stricter communication scope boundaries without changing the USER_PACKAGE authority model or runtime architecture.
- Refined Assistant communication behavior to reduce unsolicited recommendations, summaries, conclusions, and future suggestions while preserving required operational communication.

### Removed

- `README.txt` from the active public repository structure.

### Security

- Reviewed the public package for exposed credentials, private keys, passwords, personal contact details, private links, and client-restricted information.
- No known security or privacy blocker was identified in the reviewed v1.0 baseline.

## [1.0.0] - 2026-07-15

### Added

- Initial private USER_PACKAGE baseline.
- User authority and governance documents.
- Assistant behavior and output standards.
- Documentation structure, writing, layout, property-value, visual-boundary, and prompt-writing standards.
- Documentation refactoring, synthesis, consolidation, and streamlining methods.
- Patch delivery, script delivery, and build-order capabilities.
