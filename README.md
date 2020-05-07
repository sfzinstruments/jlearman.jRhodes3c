# sfz-jRhodes3c-looped

SFZ multi-layer instrument: 1977 Rhodes Mark I, looped

## jRhodes3 family

jRhodes3 is my sampling of my 1977 Rhodes Mark I Stage Piano, which I purchased
new back in 1978. This sample set is not intended to be a jack-of-all-trades
Rhodes, but rather, it's how I set up and used my Rhodes. It was recorded with EQ,
with a treble boost and low-mid scoop, emphasizing the bell tones, but with
substantial bark on the higher velocity layers. There are 5 layers, sampled
to peak at 3dB difference per layer at on the low notes and to maintain volume
throughout each layer. Not all layers are full-keyboard width, higher notes
don't change timbre as much.

The set includes 67 16-bit looped samples, with up to 5 velocity layers,
sampling every 4th white key.
The samples were recorded directly from the harp connector.
Samples are encoded in lossless FLAC format to reduce disk space.

## This version: jRhodes3c

jRhodes3[b]c[/b] is a looped version, with stereo option.  Samples are looped after a
few seconds, to save memory and disk space.

The stereo effect is a mild pitch-shift doubling to create a stereo image, applied in mid-side effect so that it cancels out when summed to mono.

Three .szf files are included:
* jRhodes3c-looped-both.sfz - mono is MIDI Program 1, stereo is MIDI program 2
* jRhodes3c-looped-mono.sfz - mono only
* jRhodes3c-looped-stereo.sfz - stereo only

## How-to

Click the green "Clone or download" button above, and choose
"Download ZIP".  Unpack the .zip file into a folder of your choice,
and load the result into your sample player.  I use Sforzando, which
supports FLAC.

## Sampling Details

The samples were recorded around 2006, from a Rhodes I had bought
new in 1978.  The samples were recorded directly from the harp
connector, with EQ applied to give the tone I usually used, enhancing
the bell-like quality and carving out low mids.  Two control files
are provided; one is the original mono, and the other "stereo" has
a stereo image added by applying a 2 cent pitch shift using mid-side
technique (so the effect cancels completely to the mono, when
summed to mono.)  Noise was removed from the samples using CoolEdit 96.
The samples were recorded around 2006, and I no longer have the
piano.

Samples in this set were looped to reduce memory footprint.
For full-length unlooped samples, see jRhodes3d.

This is not intended to be the authentic original unprocessed Rhodes;
it's intended to be what I wanted the Rhodes to sound like most of
the time.

Regarding the naming convention: the 3 is because this was my
third sampling attempt.  (The first was a single-velocity sampling
for dev test purposes only.  The second was aborted for technical
reasons I don't recall.)  The "c" identifies this as the 3rd
attempt at processing the samples or mapping the keyboard.

The "d" mono samples are identical to the "c" samples but full-length.
The "d" stereo samples have the same effect applied as "c" but
using different tools (SoX library rather than r8brain.)

I lost the original sample recordings in a home fire, but fortunately
I did have distribution copies of the original looped and unlooped
soundfont files, and these sample sets are recreated from them.

See http://github.com/jlearman repos beginning with "sfz" for other
sampled instruments.

