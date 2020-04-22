# discoDSP OB-Xd
![](https://www.discodsp.com/img/obxd.png)

# About

OB-Xd is based on the Oberheim OB-X. It attempts to recreate its sound and behavior, but as the original was very limited in some important ways a number of things were added or altered to the original design. It was designed to sound as good and as rich as the original. It implements micro random detuning which is a big part of that sound. However, it was not designed as a self-contained completely independent soft-synth. It needs to be contained within a VST framework where things like transposition, automation, layering, arpeggiation, etc., are available.

While not copying originals, some of the features were taken to a better point. Continuous blendable multimode filter (HP-Notch(BP)-HP in 12 dB mode and 4-1 pole in 24 dB mode). Also, like many synths of the OB-X's generation, the OB-Xd has no internal effects so its sounds and textures can be greatly enhanced by the use of additional processing like chorus, reverb, delay, etc.

Thanks to 2Dat for the original OB-Xd and Soshi Studio for giving the rights to continue this wonderful product.
Also thanks to [KVR artist creating some amazing skins!](https://www.kvraudio.com/forum/viewtopic.php?f=1&t=471926)

# Binaries

**Release** https://www.discodsp.com/obxd/

**Nightly**  https://www.discodsp.net/obxd-nightly/

# Building

Source is compiled with [JUCE 5.4.3](https://github.com/juce-framework/JUCE/archive/5.4.3.zip), VST2 SDK and VST3 SDK. Since VST2 is only possible to use with a Steinberg permission not possible to obtain right now, it's recommended to disable VST (legacy) prior to generating the exporters with Projucer.
