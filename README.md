![image alt]([https://github.com/LANDR-3D/LANDR.github.io/blob/main/LANDR%20Logo_Build%20Plate.png?raw=true](https://github.com/LANDR-3D/LANDR.github.io/blob/main/LANDRWiki%20header.png?raw=true))

# LANDR Wiki

## How to Use the LANDR 500

---

### Getting Started

#### Initial Setup:
1. Plug in and turn on the printer.
2. Level the print bed even by hand for the initial setup.
3. Calibrate the z-offset
4. Load the filament.

#### First layer calibration.
1. Z-offset: Use the printer’s "Z calibration" under More option to manually adjust the bed height. Place a piece of paper under the nozzle and move it until the nozzle lightly scrapes the paper—there should be slight resistance, but not too tight.
2. Check the First Layer: As the printer starts, the first layer:
3. Too High: If the filament doesn’t stick or looks stringy, lower the bed slightly.
4. Too Low: If the nozzle drags or the filament squishes too much, raise the bed slightly.
5. Fine-Tune Z-Offset (if needed):While the printer is printing under fine tuning it is possible to adjust it real time and save it for the next time.

### Printing Process

#### Starting a Print:
Importing the model, into the slicer, and sending to the printer

#### Ways to send print files to printers:
Through Wi-Fi: On the screen go More>Network On the top, there is a number. Type that into a browser to get access to it. The two device must be on the same network for it to work.
Flash Drive: Take a fat32 flash drive and copy the gcodes onto the flash drive. Once the flash drive has the desired gcodes on it, plug it into the printer front USB slot. Wait a little bit to shows up under the print section.

Monitoring the Print:
We recommend to check on the machine regularly while it is running.

#### Loading filament
1. Click the button shown and click “Load Filament” to position the toolhead for loading.
2. Push the filament into the PTFE tube on the back until it hits the end of it.
3. Heat up the extruder to the desired temperature for that filament.
4. Once it reached the temperature, click extrude and load.

#### Unloading filament
1. Click the button shown and click “Load Filament” to position the toolhead for loading.
2. Heat up the extruder to the desired temperature for that filament.
3. Once it reached the temperature click extrude and unload..

   ---

### Troubleshooting
#### Common Issues and Solutions
Print file not showing up after plugging the flash drive in:  If the file doesn’t seem to show up even after waiting 5 minutes, click the refresh button on the top, and it looks like two arrows going in a circle. If that still doesn’t fix the problem, restart the machine.

#### Screen doesn’t turn on: 
Make sure that the printer has power, and the switch on the back and at the front is turned on.

#### Bed Adhesion Problems:
Issue: First layer not sticking.
Solution: Adjust bed level, clean bed surface, use adhesion aids adjust bed temperature.

#### Nozzle Clogs:
Issue: Filament not extruding.
Solution: Clean the nozzle with a needle, or use cold pull.

#### Stringing:
Issue: Filament oozing between parts.
Solution:  Dry the filament, Increase retraction settings, lower temperature.

#### Warping:
Issue: Corners lifting from the build plate.
Solution: Clean the bed and/or add adhesive to it,, use a brim or raft in slicing.

#### Layer Shifts:
Issue: Layers are misaligned.
Solution: Check for loose belts, ensure print bed is secure, check for obstructions.

#### Under extrusion or no extrusion:
Issue: Part comes out see through or/and clicking coming from the extruder.
Solution: Switch nozzle and recalibrate z-offset. If the issue is still consisting, switch the hot end out.

---

### Error Codes and What They Mean

#### Heater is not heating at expected rate: Description: The printer stop with the error code on the screen.
Solution: 
1.Press Firmware restart and heat up the bed and the toolhead.
2. If both heats up properly, change the slicing option to reduce stress on the toolhead or the bed. This can be done by reducing the maximum flow rate, turning down the temperature, or increasing the temperature of the environment.
3. If the temperature not increasing after requisition it to increase, it could be a broken wire,   broken hotend or a broken mainboard.

#### ADC out of range : The printer is reading a wrong temperature because of a broken wire or a loose wire.
Printer Maintenance
Regular Cleaning:
Clean the build plate, purge bucket, nozzle, extruder and chamber regularly.
Lubrication: 

---

## FAQ

#### General Questions

##### Q: What software should I use for slicing?
A: We recommend to use Landr slicer.

#### Operational Questions

##### Q: How do I change LED brightness
A: LED slider can be found under More>pin

##### Q: How do I pause or resume a print?
A: Press the pause button to pause the print and press the resume button to resume it.

##### Q: What should I do if the print fails halfway through?
A: Stop the print with the stop button and investigate the cause.

##### Q: Do I have to do anything with the printer if I printer high temperature materials with it?
A: Yes, if the hotend needs to heat up higher than 300°C, the Silicone Sock needs to be removed.

##### Q: Is it normal for the hotend or/and bed temperature to fluctuate?
A: It is normal for it to fluctuate a bit. This can be reduced by doing a PID tune.
PID tune can be done by clicking on the heater that needs tuning the same way as changing the temperature for it, typing in your normal operating temperature to it and hitting the Calibrate PID button to start the calibration. This takes a couple of minutes and afterwards it will ask you if you would like to save the new PID. Hit yes and the system will reboot with the new updated PID.

#### Maintenance Questions

##### Q: How often should I replace the nozzle?
A: Nozzles need to be replaced when experiencing partial or full clog. After every nozzle swap z-offset needs to be redone.

##### Q: How do I swap a nozzle?
1. Heat up the nozzle to 300°C and using a 7mm spanner take it out.
2. Put the new one in and tighten it while it's at 300°C.
3. After a nozzle swap, the z-offset needs to be redone.




