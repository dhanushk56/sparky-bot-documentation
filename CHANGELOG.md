# 📝 Changelog

All notable changes to SparkyBot will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [2.1.0] - 2026-01-20

### Added
- `/lv text` command – Set custom level-up message text
- `/counting setsavecooldown` command – Configure save cooldown
- Premium emoji support – All emojis now use custom, premium emojis from Emoji.gg
- Translation module – 100+ languages supported
- Forum auto-lock – Automatically lock forum posts after set time
- Music system – Full music playback with YouTube, SoundCloud, and Spotify

### Changed
- Improved help menu with better organization
- Better error messages for permission checks
- Faster command processing
- All `---` separator lines removed from codebase

### Fixed
- Fixed issue with economy daily rewards
- Fixed counting channel cooldown bug
- Fixed ticket system permission checks
- Fixed music queue persistence

---

## [2.0.0] - 2026-01-01

### Added
- Complete rewrite with cog-based architecture
- 26 cogs with 300+ commands
- Web dashboard (coming soon)
- Advanced moderation system
- Ticket system with forms and reviews
- Economy system with 300+ shop items
- Giveaway system with role requirements
- Application system with manager roles
- JTC (Join-to-Create) voice channels
- Reaction roles with exclusive modes
- Anti-nuke protection with 22+ events
- Invite tracking with fake detection
- Verification system with captcha
- Reports and suggestions system
- AutoMod with per-module whitelists
- Counting channel with saves and streaks
- Custom prefix support
- Embed builder and rules panels
- Welcome and goodbye system
- YouTube notifications with filters
- Translation with auto-translate
- Music with 24/7 mode
- Forum auto-lock
- Owner-only management commands
- Global poll system
- 24/7 mode approval system

### Changed
- Migrated from prefix-only to slash commands
- Improved data persistence
- Better error handling
- Enhanced performance

### Removed
- Old command handling system
- Legacy database structure

---

## [1.5.0] - 2025-12-15

### Added
- Economy system basic commands
- Leveling system
- Basic moderation tools

### Fixed
- Various bug fixes
- Performance improvements

---

## [1.0.0] - 2025-11-01

### Added
- Initial release
- Basic moderation commands
- Simple ticket system
- Welcome/goodbye messages
- Reaction roles
- Logging

---

## [Unreleased]

### Added
- Web dashboard development
- Database migration to PostgreSQL
- Redis caching support
- API endpoints for external services
- Analytics and metrics

### Planned
- Advanced statistics
- Custom command creation
- Server templates
- Premium tier system
- Mobile app
