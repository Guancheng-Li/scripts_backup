# HeadSet setup script
An awesome script for setup ear phone on ubuntu.

### Solves the following problem:
Earphone connected correctly but failed to get any sound.
Speaker can play the audio correctly...
Setup the following package still cannot work:
```
sudo apt-get install --reinstall pulseaudio pulseaudio-utils pulseaudio-module-bluetooth
sudo apt-get install --reinstall bluez bluez-alsa bluez-audio bluez-gstreamer bluez-hcidump bluez-tools bluez-utils
```
But execute `a2dp.py` from following link works, amazing!
`https://gist.github.com/pylover/d68be364adac5f946887b85e6ed6e7ae`
