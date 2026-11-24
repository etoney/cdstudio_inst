# Castle Danger Studio instruments

Sampled instruments for **Heresy** in [Castle Danger Studio](https://castledangermusic.com/project/castle-danger-studio/). Heresy loads them straight from this repo through jsDelivr.

All samples are public domain (CC0 1.0), from VS Chamber Orchestra: Community Edition by Versilian Studios. See [CREDITS.md](CREDITS.md).

## Layout

- `index.json`: the list of instruments (id, name, group, type).
- `<id>/instrument.json`: zones (root note, velocity range, loop points, peak level, sample count) and the source.
- `<id>/*.mp3`: the samples, trimmed and loop-crossfaded, 44.1 kHz stereo.

To add an instrument, put its folder here and add it to `index.json`. Heresy also needs the id added to its Instrument list.
