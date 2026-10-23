# Tape Fiasco 2 v2.0.4.974

Built on GitHub Actions for macOS, Windows and Linux from source commit 112a3a14b5e661c42ecfbdbb256f38575f362bea.

Changes since the previous desktop release (2.0.2.937):

- 31 new effects, for 62 in total: HOWL, LOSSY, MIRROR, TAPE and UNDERTOW (Distortion); CHROMA, COMB, CONTRAST, LIQUIFY, SEPARATE, SMEAR, TRANSMIT and VESPER (Filter); STRINGS (Resonate); MAGNET, STILLS, TRIAD and WARP (Pitch); CHOPPER, LOOP, SCANNER, STRUM and WENDY (Time); FISSION and FLYBY (Modulate); CADENCE, GRANULAR DELAY, REEL and SPECTRAL DELAY (Delay); GRANUVERB (Reverb); TRANSIENT (Dynamics).
- The FX list groups the effects into ten collapsible categories.
- New controls on many existing effects, including BITROT, CIRCUIT BEND, PRISM, TOOTH, FORMANT, SIEVE, CRYSTAL, PITCH SHIFT, CHORUS, FLANGER, PHASER, CLANG, SPIRAL, DATTORRO, DRIP, GATE and SQUASH.
- Latency compensation for the FFT effects, on by default and switchable in the cog menu: the plugin reports their delay to the host and stays in time with your other tracks.
- The Perform page XY pad keeps following the mouse after a click away from the handle.
- Fixed FX page lag on Windows and Linux when hovering or scrolling the FX list.
- Removed the update notes screen from the previous release.

Some existing presets sound different: engine fixes change PRISM's band-pass, high-pass and notch modes, WAVEFOLDER with several folds, CLANG's TRACK, SPIRAL with DUCK off, and SQUASH. Sessions that use FFT effects now play in time, earlier than before.

Downloads:

- macOS: Universal AU and VST3 (Apple Silicon and Intel), delivered in a Developer ID signed, Apple-notarized and stapled PKG installer.
- Windows: x64 VST3, an EXE installer and a VST3 bundle for manual installation.
- Linux: x86_64 VST3 with installation instructions.

The macOS and Windows ZIPs retain v2.0.2.937 as a fallback, as in the previous release. Install v2.0.4.974 for the current features and fixes.

The plugin's update checker reads the public latest.json manifest. Automatic checks may use a cached result for up to 24 hours; Check for updates in the cog menu refreshes immediately.
