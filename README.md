# Changelog

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
