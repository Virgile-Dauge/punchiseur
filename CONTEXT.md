# PUNCHISEUR

A live **instrument** for "punching up" a recorded track you like: load it, pick a genre Preset, and shape electronic-music energy (acid, hardcore, psytrance, …) over the original in real time with Strudel patterns. The point is that you *play* it — it's not a one-click generator.

## Language

**Source Track**:
The recorded audio you feed in (e.g. an mp3 of a rap, classical, or protest song). Used as a sample inside Strudel — its performance is never re-synthesised, only analysed and built around.
_Avoid_: song, input. (In Strudel a "sample" is any audio file the engine plays; the Source Track is one specific sample, so don't use the bare word "sample" to mean it.)

**Preset**:
A named genre recipe (Acid, Hardcore, Psytrance, …) applied to a Source Track. Bundles which signature **Layers** to add, how to process the Source Track, and a target feel/tempo. Additive-led: stacking genre Layers is the backbone; processing the original is seasoning.
_Avoid_: effect, filter, style (reserve "Preset" for the whole genre recipe, not one of its parts).

**Layer**:
A single Strudel-generated part stacked onto the Source Track — e.g. a kick pattern, an acid bassline, a hi-hat roll. A Preset adds several Layers. Pitched Layers are defined in scale degrees (key-relative), not fixed notes, so they can be harmonised to the Source Track's key later.
_Avoid_: track, stem, channel.

**Beat Grid**:
The Source Track's detected tempo and beat positions, expressed in Strudel's cycle timing. Every Layer aligns to it; it's also what the Source Track is stretched against when matching a Preset's tempo.
_Avoid_: timeline, click track.

**Macro**:
A named, continuous control a Preset exposes (e.g. Intensity, Drive, Density, Bass) that shapes the Punch in real time. Nothing controls the Punch except through Macros. v1 surfaces them as on-screen knobs; a later voice/fuzzy layer nudges the same Macros ("donne-moi plus de drive").
_Avoid_: knob, slider, parameter (those are the UI or representation; the Macro is the named control itself).

**Punch**:
The live result of applying a Preset to a Source Track — the Source Track plus its added Layers and processing, playing in Strudel and shaped in real time through Macros. Also the verb: to _punch up_ a Source Track.
_Avoid_: remix, mix, set, patch.
