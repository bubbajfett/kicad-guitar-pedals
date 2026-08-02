
# dynacomp


Guitar Pedal PCB based on MXR Dyna Comp compressor pedal.

The original version of this had a footprint error (the DIP 8 was the wider 10mm DIP-8 footprint) but this was bodged in the build.

This seems to be working correctly, but testing compression pedals is kind of weird.   This depends on a CA3080, which I had a stash of from long ago, apparently made by Harris.    It seems to work, passing audio.   Volume controls work, and the compression sensitivity also seems to work.    At max sensitivity, a note splutters out after about 8sec, which is kind of weird.

Because the CA3080 is sort of unobtainable now, except at pretty steep prices, I made a 2nd version which uses 1/2 of the LM13700 instead.    This is not yet verified, and is marked so in the .kicad_pcb file.


All registered trademarks are owned by their respective owners.

