# Tape Fiasco 2 v2.0.0.810

This release contains the current Tape Fiasco 2 desktop plug-ins:

- macOS Universal AU and VST3 (`arm64` and `x86_64`) in a double-click `.pkg`
  installer, signed with Developer ID, notarized by Apple, and stapled for
  offline validation
- Windows x64 VST3 in an `.exe` installer
- Linux x86_64 VST3

The macOS and Windows downloads also include the previous v2.0.0.660 installer
as a stable fallback. Install v2.0.0.810 unless you specifically need to roll
back.

Highlights:

- Distort now has LOW CUT and HIGH CUT frequency-focus controls, limiting
  nonlinear processing to the selected band while leaving frequencies outside
  it clean
- New Gate, Pitch Shift, Mangle, and five-mode parametric EQ effects
- A redesigned granular Scatter effect in the reorderable FX chain, with
  clocked size/density, musical pitch intervals, synchronized scramble reads,
  and extensive timing and sound-quality improvements
- Stretch Scatter now follows host BPM and PPQ automatically; GRAIN selects
  `1/16` through `1/512` jump divisions while standalone/no-clock operation
  retains the original free-running behavior
- External sidechain input support for Animate envelope followers
- Expanded themes and runtime theme selection
- Numerous click-safety, visualization, modulation, iPad/AUv3, and stability
  improvements

Choose the ZIP for your operating system below. No GitHub account is required.
