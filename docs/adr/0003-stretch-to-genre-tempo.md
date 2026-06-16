# Stretch the Source Track to the genre tempo

When a Preset's genre tempo differs from the Source Track's BPM (e.g. a 90 BPM rap into a ~145 BPM psytrance), we time-stretch the Source Track to the genre tempo so the result feels authentically like the genre — rather than the simpler path of keeping the original tempo and adapting the Layers to it. This commits us to a **pitch-preserving** time-stretch engine (so vocals don't chipmunk).

The specific engine (signalsmith-stretch / SoundTouch / Rubber Band — note Rubber Band's GPL/commercial licensing) is **pending the SOTA scan**.

## Consequences

- A pitch-preserving time-stretch engine is a hard dependency from v1, not an add-on.
- Beat/BPM detection of the Source Track is required to compute the stretch ratio.
