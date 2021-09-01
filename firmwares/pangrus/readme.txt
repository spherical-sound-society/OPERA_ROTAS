PANGRUS EDITION (ver 1.0)
Courtesy of Andrea (Pangrus). Thank you so much!!

This firmware has MIDI working (on OPERA ROTAS rev 0.9 and higher). If you have a previous version, you will need a chiclet and a little bit of hacking to get the midi working

This version uses a different bootloader, so if you want to flash it it could be convenient to get a new bluepill, flash this bootloader and then flash the pangrus firmware, so now you can change firmware just replacing one or the other bluepill. If your bluepill is low or medium density (64kb) use hid_generic_pc13.bin bootloader. If your bluepill is high density (128kb) use hid_generic_pc13_hd.bin bootloader.

If you dont know how to do it, you can get preflashed microcontrollers in my stores

The keyboard shorcuts are somewhat different. Also the songs has changed. The keys are:

REC - start/stop. The ">" sign in the upper left appears when the OR sequencer is running.
AUTO - engage AUTO mode. In AUTO mode, the active channel changes every step. When you move a knob, the correspondig parameter of the active channel is affected.
AUTO + Pressing the keys from 1 to 8 load the sound presets
LOCK - engage LOCK mode. Pressing the keys from 1-8 the corresponding channel toggles from locked to unocked.
EDIT - engage EDIT mode. Press the keys 1-16 to edit the active pattern. The pattern is shown on the leds.
CHAN - engage CLEAR mode. Pressing the keys from 1-8 clears the corresponding channel.
RND - engage RANDOM mode. Pressing the keys from 1-8 randomize the corresponding channel. Randomization is made with the euclidean algorithm.
SAVE - engage MUTE mode. Pressing the keys from 1-8 the corresponding channel toggles from muted to unmuted.
SHIFT + AUTO - toggles slave MIDI mode.
SHIFT + LOCK - locks all channels.
SHITH + CHAN - clears all channels.
SHIFT + RND - Select generative mode. In GEN1 mode every 16 step the gates of one pattern and one sound parameters is randomized. In GEN2 mode gates are unchanged; every step one sound parameter is randomized. Bpm selection is disabled.
SHIFT + SAVE - mutes all channels.
