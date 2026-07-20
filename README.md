## [3.5.0] - 2026-07-21

### ✨ New Features
- **Native License Activation**: Added robust online license activation interface and backend key verification routines.
- **Automated App Updates**: Integrated Tauri 2.0 native updater plugin (`@tauri-apps/plugin-updater`) for seamless auto-updating of the desktop client.
- **Enhanced Telemetry & System Diagnostics**: Implemented automated background telemetry reporting and system diagnostics for performance and stability tracking.

### ⚡ Improvements & Refactoring
- **Tauri 2.0 Backend Integration**: Upgraded Tauri native commands, system metrics monitoring, and panic tracking in the Rust backend.
- **Live Sales Dashboard**: Added real-time sales potential analytics, photo sales tracking, and custom desktop toast notifications for new sales events.
- **Multi-Batch Upload Pipeline**: Optimized folder scanning, EXIF metadata extraction, S3 direct upload authorization, and multi-threaded video compression.
- **Multilingual Support**: Added full English (`en`) and Indonesian (`id`) localization support across all tabs and components.
