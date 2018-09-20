SYSTEM80 JOVE Multimode Filter
============



Roland Jupiter 6 inspired multimode filter in 14HP Eurorack format. IR3109s replaced with LM13700 OTAs.
Selectable 24 dB low pass, bonus 2 pole 12 dB low pass, band pass and high pass modes.

Product page: http://system80.net/product/jove/<br>

Demos:<br>
https://soundcloud.com/system_80/sets/jove-demo<br>
https://soundcloud.com/system_80/sets/jove-mimoid-demo<br>
https://www.youtube.com/watch?v=VFNtQRDSUw4


EDA files generated in KiCad 4.0.2. Schematic library here: https://github.com/minisystem/MyKicadLibraries/blob/master/MySynthParts.lib
KiCad GitHub libraries required as well. :/
Front panel design by Bartek Kawula.<br>
Hardware design by minisystem: info@system80.net

PCB
===
See /Gerbers/JOVE-gerbers-1.5.zip

BOM
===
Octopart BOM: https://octopart.com/bom-tool/0BVEzM8i<br>
NOTE 1: R66 and R67 can be 0805 10R resistors or PTC fuses (see BOM for part number)<br>
NOTE 2: C1, C11, C28, C29 can be either 10 pF or 22 pF

CALIBRATION
===========
Feed one of the inputs a 10 Vpp ~50 Hz square wave. In 12 dB mode with frequency and resonance knobs both at minimum (fully CCW), adjust VR5 so that the filter is fully closed. This is best done by ear using headphones. Then switch to HP mode with frequency knob at max (fully CW) and listen to ensure most of the high frequency harmonics are gone. There's a sweet spot where maximum attenuation in both modes can be achieved. The resonance trimmer is used to ensure that there is minimum resonance when the resonance knob is fully CCW. Set the frequency knob at about 12 o'clock and look for a resonance peak on the square wave in 12 dB mode using an oscilloscope. Adjust the input gain so that the output square wave is 10 Vpp. Then use VR7 to to trim away the resonance peak so that the square wave is flat. 

Acknowledgements
================
The idea to hybridize the audio input and control voltage stages from the MKS80 and SH101, respectively, comes directly from
the AMSynths AM8060: http://www.amsynthstore.co.uk/

LICENSE
=======
cc-by-nc-sa
https://creativecommons.org/licenses/by-nc-sa/4.0/<br><br>
Please note the NON-COMMERCIAL (NC) clause of the Creative Commons license.  You do not have permission to build and sell JOVE for monetary compensation.
Make one for yourself, make an extra and sell it to your friend? That's cool. Make several and sell them on eBay/ModularGrid/Tindie? No, don't do that! :)<br><br>
The NC clause isn't going to be around forever and eventually derative works for commercial use will be allowed, but currently commerical use is prohibited by the license. <br><br>
Please also note the ShareAlike (SA) clause of the license: if you create a derivative work, please ensure that it is distributed under the same license and is not used commercially.