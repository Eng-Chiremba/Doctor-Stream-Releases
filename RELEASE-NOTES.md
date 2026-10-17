# Doctor Stream 1.1.1 — release notes

Paste a complete YouTube video link and Doctor Stream automatically finds the
video after 450 ms without further edits. Find video and Enter remain available
for immediate lookup. They cancel the pending automatic lookup and share the
same busy guard, preventing duplicate requests. Incomplete and unsupported links
do not trigger background lookup. Download permission and the Download button
remain explicit; no media download starts automatically.

Includes the 1.1.0 flat workspace, visible About, saved preferences, queue actions,
parallel video/audio transfers, pause/resume and in-place upgrades.

Folder contents:
- Doctor-Stream-1.1.1-Windows-x64-Setup.exe — installer to distribute.
- Release notes.md — these release notes.

Run Setup to install or upgrade. It replaces the existing Doctor Stream version,
keeps one Windows Apps entry and preserves settings, history and downloaded media.
Close the application before upgrading. No background updater is installed.

The focused automatic-lookup checks, Release publish and required extension
checks passed. Installation succeeded, all 411 installed files match the release,
and current settings/history were preserved. No repeated media-download testing
was needed for this UI-only patch.

Public release still requires trusted publisher signing, clean Windows testing
and exact bundled-tool source/build redistribution review. The installer remains
unsigned. Connection and source/CDN limits still affect download speed.

Installer SHA-256: 26c1fc6885a5018dd11fd9e3a65665c86f85e37a6cff048c8956c85d9b4ba1a5


