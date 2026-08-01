# Tape Fiasco 2 v2.0.0.825

This release contains the current Tape Fiasco 2 desktop plug-ins:

- macOS Universal AU and VST3 (`arm64` and `x86_64`) in a double-click `.pkg`
  installer, signed with Developer ID, notarized by Apple, and stapled for
  offline validation
- Windows x64 VST3 in an `.exe` installer, with the raw VST3 bundle also
  included for manual installation
- Linux x86_64 VST3

The macOS and Windows downloads also include v2.0.0.660 as the stable fallback.
Install v2.0.0.825 unless you specifically need to roll back.

Highlights:

- Fixed manual Stutter capture rollover briefly replaying the end of the
  previous capture
- Fixed Stutter Sequencer ON steps briefly leaking dry audio or clicking,
  including the first capture after transport starts or the host wakes
- Changed the default Stutter CAPTURE length from 4/4 to 2/4; existing sessions
  and presets retain their saved CAPTURE setting

Choose the ZIP for your operating system below. No GitHub account is required.
