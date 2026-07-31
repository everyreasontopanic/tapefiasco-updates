# Tape Fiasco 2 v2.0.0.821

This release contains the current Tape Fiasco 2 desktop plug-ins:

- macOS Universal AU and VST3 (`arm64` and `x86_64`) in a double-click `.pkg`
  installer, signed with Developer ID, notarized by Apple, and stapled for
  offline validation
- Windows x64 VST3 in an `.exe` installer, with the raw VST3 bundle also
  included for manual installation
- Linux x86_64 VST3

The macOS and Windows downloads also include the previous v2.0.0.660 installer
as a stable fallback. Install v2.0.0.821 unless you specifically need to roll
back.

Highlights:

- Fixed restored Animate RANDOM modulators remaining idle until the plug-in
  interface was opened
- Fixed Stutter Sequencer timing when playback starts mid-bar or after a host
  sleeps, seeks, or wakes the plug-in
- Stutter Sequencer step changes now land on exact audio samples rather than
  host audio-block boundaries

Choose the ZIP for your operating system below. No GitHub account is required.
