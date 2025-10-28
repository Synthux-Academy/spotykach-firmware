# Changelog

### v0.0.27
- new overdub behavior
  - non-destructive, i.e. doesn't print back the playback output
  - feedback is now working on dB scale (-60...0dB)
  - works in slice mode
  - stop overdub on tapping `Play`
- pitch tweaks
  - `Alt`+`Pitch` snaps to +- fifth, +- 1 octave, +- 2 octaves
  - LED feedback on snapping pitch
- fixed / improved size calculation in slice mode
- fixed reverse in slice mode
- removed stopping on changing the pitch in slice mode

### v0.0.26
- prevent tremolo upon cable insertion
- fixed size change in slice mode
- fixed time stretching
- limited minimum slice length in slice mode to 1/16th
- LED tweaks

### v0.0.25
- fixed random metronome
- no "tremolo" in reel mode
- position modulation works in slice mode
- LED feedback improvements

### v0.0.24
- FXs
- Updated LEDs
- Continuous modulation in real mode
- Various tweaks and bug fixes

### v0.0.23
- envelope follower
- speed and mix knobs remember their values
- crossfader works in split-mono mode
- prevent leaks of the old recordings when buffer wraps around

### v0.0.22
Fixes the issue with recording introduced in the previous version.

### v0.0.21
This one changes the way recording is stopped and fixes the issue that could cause pop / burst of noise at the end of the loop.

### v0.0.20
A tiny hot fix that should eliminate probability of loud sound bursts in drift mode.

### v0.0.19
- drift mode
  - in this mode the deck plays three loops shifted, different in size and layered on one another.
  - changing size and position chnage ratios between loops as well.
  - modulation in drift mode is applied continuously in contrast to slice mode, where modulation is applied at the beginning of a slice.
- stereo/mono switch.
  - in the stereo mode input A serves as L, input B - as R. The inputs are shared between decks. Deck outputs are then mixed through a crossfader and sent to the out A/B (L/R respectively).
  - in mono mode input A is dedidcated to deck A and B - to B. Same with outputs. Please note that if input B is not plugged in, input A works for both A and B. Crossfader is disengaged in this mode.
- Spotykach become more stable overall
- slice mode tweaks. The default slice is now 1/8th.
- higher LFO frequency (up to 12Hz)
- sequencer works properly with the reel mode
- reverse works without skipping parts of the loop
- I/O mix and crossfader ranges adjusted so there should be no leaks anymore   

### v0.0.18
- the preinstalled firmware of the July release
- no user facing changes comparing to previous version
