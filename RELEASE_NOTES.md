# Tape Fiasco 2 v2.0.2.937

Built on GitHub Actions for macOS, Windows and Linux from source commit 494d5eeb05ce75086d28dc5fd3557f19d24c8889.

Changes since the previous desktop release (2.0.1.894):

- SERIAL/PARALLEL FX routing.
- Per-effect gain compensation from -12 to +12 dB.
- PITCH SHIFT now includes Pitch, Frequency and Ring modes, fine tuning, stereo spread, delay, feedback tone, and scale/root snapping.
- LINKED/INDEPENDENT Stretch speed and pitch controls.
- Improved DRIP spring-reverb decay and recovery from invalid audio.
- Shift-drag FX knobs for fine adjustment.
- Updated release notes shown on first open and available again from the version number.

Downloads:

- macOS: Universal AU and VST3 (Apple Silicon and Intel), delivered in a Developer ID signed, Apple-notarized and stapled PKG installer.
- Windows: x64 VST3, an EXE installer and a VST3 bundle for manual installation.
- Linux: x86_64 VST3 with installation instructions.

The macOS and Windows ZIPs retain v2.0.0.828 as a fallback, as in the previous release. Install v2.0.2.937 for the current features and fixes.

The plugin's update checker reads the public latest.json manifest. Automatic checks may use a cached result for up to 24 hours; Check for updates in the cog menu refreshes immediately.
