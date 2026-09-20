# Current guitar pedal projects 

Current count of pedals in this repo is:  34.

The latest change is to add a PDF in the root of each pedal directory, which has the readme, the schematic as an image, and the front and back layout of the PCB (F.Cu+F.Silkscreen, B.Cu+F.Silkscreen). Also a BOM of the parts is included.    This was all done scripted using kicad-cli  in a VM (Fedora 44, Kicad 10 !!!) as the Kicad 7 versions of this did not work very well.   I will add pics of the real tested boards as an addendum to these.    This change was a result of some feedback I recieved about the lack of clarity of what is in this repo.

These pedals have been a learning exercise for me in KiCad. Any guitar pedal PCB published here has been built and tested. In some cases, more than two versions of boards have been created.   The worst case was 5 versions.

The main idea for doing my own PCB is to allow me to change the footprints and merge and/or hack pedal schematics to come up with new ideas.
The other reason is I am redoing my pedalboard to convert from side-jacks/veroboard layout to  top-jacks/pcbs.   I have gotten to dislike veroboard layouts.

I am an amateur in this.   Also this has been a huge learning exercise.    I've tried to be consistent

*   back of board mounted POTs
*   common format pinheader so to be able to use 4pin dupont connector or JST connector when building the
*   power on the top jack connector, with diode protection.
*   led on the stomp switch
*   125B form factor.    Top jacks in a 1590B is really hard.

One thing I have learned is that the text size on some of these boards is below
the JLPCB minimum recommended size; the text looks fine in osh-park boards.   

Putting these pedal layouts out there for any interested party.   Do what you want with them. 

Here are the current repo contents.   These have all been tested outside the box,
and multiple have been successfully boxed.  8 have been boxed and are 
now on the pedalboard. 


| PEDAL | BUILD DOC | Verified|
| ----  | -------   | ------- |
| Delay/deep_blue_delay | [deep-blue-delay](./Delay/deep_blue_delay/deep_blue_delay.pdf) | Y |
| Util/stomp-chargepump |  [stomp-chargepump](./Util/stomp-chargepump/stomp-chargepump.pdf) | Y |
| Util/stomp-3pdt | [stomp-3pdt](./Util/stomp-3pdt/stomp-3pdt.pdf) | Y | 
| Util/top-jacks | [top-jacks](./Util/top-jacks/top-jacks.pdf) | Y |
| Distortion/percolator | [percolator](./Distortion/percolator/percolator.pdf) | Y |
| Distortion/acapulcogold | [acapulcogold](./Distortion/acapulcogold/acapulcogold.pdf) | Y |
| Distortion/fuzzface | [fuzzface](./Distortion/fuzzface/fuzzface.pdf) | Y | 
| Distortion/redllama | [redllama](./Distortion/redllama/redllama.pdf) | Y |
| Distortion/whitefuzz | [whitefuzz](./Distortion/whitefuzz/whitefuzz.pdf) | Y |
| Distortion/bigmuff | [bigmuff](./Distortion/bigmuff/bigmuff.pdf) | Y | 
| Distortion/bigmuff/bmp-ramshead  | --- | Y |
| Distortion/lizardq | [lizardq](./Distortion/lizardq/lizardq.pdf) | Y | 
| Distortion/ejfuzzface | [ejfuzzface](./Distortion/ejfuzzface/ejfuzzface.pdf) | Y | 
| Distortion/tonemachine | [tonemachine](./Distortion/tonemachine/tonemachine.pdf) | Y |
| Distortion/BMP2 | --- | Y |
| Distortion/blackdarling | --- | Y |
| Compressor/bearhug | [bearhug](./Compressor/bearhug/bearhug.pdf) | Y | 
| Compressor/engineers_thumb | [engineers_thumb](./Compressor/engineers_thumb/engineers_thumb.pdf) | Y |
| Compressor/dynacomp | --- | Y |
| Compressor/dynacomp-lm13700  | --- | N | 
| Envelope/mutron | [mutron-v](./Envelope/mutron/mutron.pdf) | Y |
| Overdrive/SFTii | [sftii](./Overdrive/SFTii/SFTii.pdf) | Y | 
| Overdrive/triple_wreck | [triple_wreck](./Overdrive/triple_wreck/triple_wreck.pdf) | Y | 
| Overdrive/ecstacy | [ecstacy](./Overdrive/ecstacy/ecstacy.pdf) | Y | 
| Overdrive/badmonkey | [badmonkey](./Overdrive/badmonkey/badmonkey.pdf) | Y | 
| Overdrive/fatdrive | [fatdrive](./Overdrive/fatdrive/fatdrive.pdf)| Y |
| Overdrive/tweed57 | [tweed57](./Overdrive/tweed57/tweed57.pdf)|Y|
| Overdrive/timmy  | [timmy](./Overdrive/timmy/timmy.pdf) | Y |
| Overdrive/KoT | [KoT](./Overdrive/KoT/KoT.pdf) | Y | 
| Overdrive/ocd | [ocd](./Overdrive/ocd/ocd.pdf) | Y |
| Overdrive/revv-g4 | [revv-g4](./Overdrive/revv-g4/revv-g4.pdf) | Y |
| Overdrive/drboogie | ... | Y |
| Overdrive/umble | [umble](./Overdrive/umble/umble.pdf) | Y |
| Equalizer/eq | [eq](./Equalizer/eq/eq.pdf) | Y | 


PCB builds in progress are

*   900 fuzz (redo)
*   Barbershop (redo)
*   Klon
*   little angel chorus
*   phase45
*   g2
*   beod
*   blackdarling
*   fy2  (shin-ey fy2)
*   bluesdriver

And 4 are stuck in the box of shame 
*   zombiechorus (9 months non-working...)
*   causalty4 phaser  (ugggh ... so close)
*   box of metal      
*   kraken






      
All the above subprojects have a gerbers/ subdir with the last gerber file I generated. Using OshPark for pcb generation.    They were done with Kicad 7.
Most were done with manual placement of the elements on the PCB, and then using freerouting to autoroute the traces.



License is the general Creative Commons.
All registered trademarks are owned by their respective owners.

