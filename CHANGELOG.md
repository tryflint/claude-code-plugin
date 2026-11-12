# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0] - 2026-11-12

### Changed

- `edit-site` now chats with the Flint agent through `start_chat`, `wait_for_reply` and `send_message`, so Flint can ask questions and follow-ups keep their context. It no longer uses the deprecated `run_background_agent` and `check_background_agent_status` tools.

## [1.0.0] - 2026-03-24

### Added

- Initial release of the Flint plugin for Claude Code
- `edit-site` skill for modifying Flint websites via background AI agents
- MCP server integration with OAuth authentication
- Site listing, background agent execution, and publishing capabilities
