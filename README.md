# M4L CC Converter

This is a Max for Live device for Ableton Live. It lets you convert CC from one controller to another (e.g. modulation -> soft pedal). It has two additional settings:

1. Only use min and max values (`0` and `127`).
2. Invert the conversion so high becomes low and vice versa.

Only using `0` (full off) and `127` (full on) reflects how a pedal works, so you can map a more continuous controller like modulation wheel, and any non-0 value will snap to "pedal down". Or if the inverse mode is enabled, only 0 will be pedal down.

This was designed to approximate palm muting a guitar in a synth. You map soft pedal to something like filter cutoff and envelope, and then use the mod wheel to "palm mute". Down is muted, up is open (or vice versa if inverse setting is off).

Whether it succeeded at emulating palm muting is debatable, but it's a useful tool nonetheless.
