Gentoo overlay containing pro audio applications.

## How to use this overlay
- Add the following entry to [`/etc/portage/repos.conf`](https://wiki.gentoo.org/wiki//etc/portage/repos.conf) and sync using `emerge --sync`
```ini
[audio-overlay]
location = /<path>/<to>/<your>/<overlays>/audio-overlay
sync-type = git
sync-uri = https://github.com/gentoo-audio/audio-overlay.git
auto-sync = yes
```
- Or if you use [layman](https://wiki.gentoo.org/wiki/Layman) add the overlay using `layman -a audio-overlay` and sync using `layman -s audio-overlay`

## Contact
Join us at the `#proaudio-overlay` channel at `irc.freenode.org` or [create an issue](https://github.com/gentoo-audio/audio-overlay/issues/new).


## Packages

### media-libs

#### libmonome
Homepage: [github.com/monome/libmonome](https://github.com/monome/libmonome)<br>
Library for easy interaction with monome devices<br>
Available versions: 1.4.1, 9999

#### zita-resampler
Homepage: [kokkinizita.linuxaudio.org/linuxaudio/](http://kokkinizita.linuxaudio.org/linuxaudio/)<br>
C++ library for real-time resampling of audio signals<br>
Available versions: 1.6.0


### media-plugins

#### artyfx
Homepage: [openavproductions.com/artyfx](http://openavproductions.com/artyfx)<br>
Plugin bundle of artistic real-time audio effects<br>
Available versions: 1.3, 9999

#### distrho-ports
Homepage: [distrho.sourceforge.net](http://distrho.sourceforge.net)<br>
Linux ports of Distrho plugins.<br>
Available versions: 20170804, 99999999

#### fabla
Homepage: [openavproductions.com/fabla2](http://openavproductions.com/fabla2)<br>
LV2 drum sampler plugin<br>
Available versions: 1.3.2, 1.9999, 2.9999

#### sorcer
Homepage: [openavproductions.com/sorcer](http://openavproductions.com/sorcer)<br>
Polyphonic wavetable synth LV2 plugin<br>
Available versions: 1.1.3, 9999


### media-sound

#### bitwig-studio
Homepage: [bitwig.com](http://bitwig.com)<br>
Multi-platform music-creation system for production, performance and DJing<br>
Available versions: 1.3.16, 2.1.1, 2.1.2, 2.1.3, 2.1.4, 2.2, 2.2.1, 2.2.2, 2.2.3

#### cadence
Homepage: [kxstudio.linuxaudio.org](http://kxstudio.linuxaudio.org)<br>
Collection of tools useful for audio production<br>
Available versions: 9999-r1, 9999-r2

#### drumkv1
Homepage: [drumkv1.sourceforge.net/](http://drumkv1.sourceforge.net/)<br>
An old-school all-digital drum-kit sampler synthesizer with stereo fx<br>
Available versions: 0.8.3, 0.8.4, 0.8.5, 0.8.6, 9999

#### ladish
Homepage: [github.com/LADI/ladish](https://github.com/LADI/ladish)<br>
LADI Session Handler - a session management system for JACK applications<br>
Available versions: 1, 9999

#### mididings
Homepage: [das.nasophon.de/mididings/](http://das.nasophon.de/mididings/)<br>
A MIDI router and processor based on Python, supporting ALSA and JACK MIDI<br>
Available versions: 20120419, 99999999

#### padthv1
Homepage: [padthv1.sourceforge.net](http://padthv1.sourceforge.net)<br>
Old-school polyphonic additive synthesizer<br>
Available versions: 0.8.4, 0.8.5, 0.8.6, 9999

#### pure-data
Homepage: [msp.ucsd.edu/software.html](http://msp.ucsd.edu/software.html)<br>
Visual programming language for multimedia<br>
Available versions: 0.47_p1

#### samplv1
Homepage: [samplv1.sourceforge.io](http://samplv1.sourceforge.io)<br>
Old-school polyphonic sampler<br>
Available versions: 0.8.3, 0.8.4, 0.8.5, 0.8.6, 9999

#### sequencer64
Homepage: [github.com/ahlstromcj/sequencer64](https://github.com/ahlstromcj/sequencer64)<br>
Reboot of seq24, a minimal loop based midi sequencer<br>
Available versions: 0.93.0, 0.93.2, 0.93.3, 0.93.4, 0.93.5, 0.94.0, 0.94.1, 0.94.2, 9999

#### serialosc
Homepage: [github.com/monome/serialosc](https://github.com/monome/serialosc)<br>
Multi-device, bonjour-capable monome OSC server<br>
Available versions: 1.4.1, 9999

#### setbfree
Homepage: [setbfree.org](http://setbfree.org)<br>
MIDI controlled DSP tonewheel organ<br>
Available versions: 0.8.4, 0.8.5, 9999

#### synthv1
Homepage: [synthv1.sourceforge.net](http://synthv1.sourceforge.net)<br>
Old-school all-digital 4-oscillator subtractive polyphonic synthesizer<br>
Available versions: 0.8.3, 0.8.4, 0.8.5, 0.8.6, 9999


### x11-libs

#### ntk
Homepage: [non.tuxfamily.org/wiki/NTK](http://non.tuxfamily.org/wiki/NTK)<br>
FLTK fork, improved rendering via Cairo, streamlined and enhanced widget set<br>
Available versions: 1.3.1000, 9999


