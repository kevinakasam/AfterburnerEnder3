# Afterburner Ender3 + Cable Chain + PINDA Probe

<img src="Images/CAD1.jpeg" width="400"/> <img src="Images/CAD2.jpeg" width="400"/>
<img src="Images/1.jpg" width="400"/> <img src="Images/2.jpg" width="400"/>

## Still in Progess
This page is currently only used to provide the files and basic instructions. More info and parts for the electronics, Raspi, BL-Touch etc will be added later. Design with the Einsy is tested. untested with Raspberry Pi and Stock/Skr Mini board! Feedback is appreciated. 

### Why?
As you can probably guess, I love the Voron design. It makes me so much fun to work with the ideas and great designs that the team around Voron has created. And since the Afterburner not only looks nice but is also quite cheap and reliable, I decided to mount it on the Ender 3. This conversion fits all Ender3 and similar machines like CR10 etc. Since the extruder had to come very far forward to be able to install the cable chain, I had a lot of space in the afterburner carriage. Therefore, I decided to integrate the limit switch into the carriage.

### A good Idea?
Definitely yes, if you can print with ABS(+). I first printed the parts out of PETG and I had a lot of problems. Besides that, the extruder is very strong like the normal BMG extruder and just works perfectly. I have been using the extruder continuously for weeks now and I am very happy with it.
If you are from Germany or the EU, please send me a message via Discord and I can print the parts for you.

### Important SAFTY notes
Do not use the original cables in the cable chain! Do not use PVC cables, these will break after some time! I replaced all my cables with silicone cables, so they do not break. You can also use PTFE cables or HELUKABEL, but this is much more expensive. If you are from Germany you can find cheap silicone cables in the online store from Conrad Electronik.

### How to print?
All parts can be printed without support (except x_motor_housing.stl; see below) and are already in the optimal orientation for printing. All Afterburner parts should be printed out of Abs(+). I'm using Esun ABS(+), this is very easy tp print. But remember that the fumes are toxic, so use an enclosure and an air filter (spoiler: I'm going to release a very powerful fan soon). I added a small support structure to the afterburner_carraige.stl. just break it after printing (see red surface below).

I'm using Gregs Modulaar Fan Duct and 5015 Mod (https://github.com/Greg191134/Voron/tree/master/Afterburner%20Optimisation). I had a small gap between the extruder and tool part, so I moved the mounting holes 1mm up (see afterburner_carriage_5015mod.stl). Since I never tested the stock Afterburner, I don't know if this "error" also occurs with the normal Afterburner or only with Greg's mod. Feel free to give me feedback.

1: Add support to the upper chain mount        |  2: break the small bridge (red surface)
:-------------------------:|:-------------------------:
![](Images/support.JPG)  |  ![](Images/break.JPG)

### BOM
* #### Rail
  * 1x MGN 12H
  * 12x M3x8mm (to mount the rail)
  * 12x M3 t-nut (to mount the rail)
  * 1x M5x8mm (to mount the limit block)
  * 1x M5 t-nut (to mount the limit block)
* #### Afterburner Carriage
  * 3x M3x20mm
  * 1x M3x5mm
* #### PINDA Mout
  * 1x M3 brass heat insert
  * 1x M3x8mm
* #### Cable Chain
  * 1 Meter 10x11 cable chain (open and closed ine works. I used the open one for better access)
  * 3x M3 brass heat insert (for mounting to the chain anchor)
  * 3x M3x5mm (for mounting to the chain anchor)
* #### X Motor Housing
  * 3x M3x5mm (to mount the x-motor)
  * 1x M3x30mm (to mount the housing)
* #### Afterburner
  * Please use Voron sourcung guide: https://vorondesign.com/sourcing_guide (Click on the Afterburner sheet at the bottom)
  * **I'm using a 23mm nema. If you want to use a 20mm one you have to modify the parts!**
* #### Afterburner 5015 Mod
  * Please check Gregs page: https://github.com/Greg191134/Voron/tree/master/Afterburner%20Optimisation
