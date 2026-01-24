# Flat Shocker

This project aims to improve OpenShock shockers by replacing the stock electrodes that are designed for dogs, not humans.  
By using a custom 3D-printed bottom case, we remove the need for a spacer, making the shocker flatter and more comfortable.

<img src="https://github.com/tommaier123/FlatShocker/blob/main/Pictures/FlatShocker.jpg" height="200"/> <img src="https://github.com/tommaier123/FlatShocker/blob/main/Pictures/HeightComparison.jpg" height="200"/>

---

## What You Gain by Doing This Modification
- Decrease total shocker height by 1.3 cm
- USB-C charging
- Customization (color, text, ...)

## What You Keep
- Full functionality including Shock, Vibrate, and Beep
- Same shocker strength (if not slightly stronger)

## What You Lose
- Water tightness. But it's still water resistant - just don't go swimming with it

---

## Bill of Materials
- 1× USB-C port [AliExpress link](https://de.aliexpress.com/item/1005008942189266.html) or [AliExpress link](https://de.aliexpress.com/item/1005010064075298.html) (There are two versions, both work) (look around there might be a cheaper listing)

  <img src="https://github.com/tommaier123/FlatShocker/blob/main/Pictures/USBC.png" height="150"/>
- 2× 15 mm stainless steel discs [AliExpress link](https://de.aliexpress.com/item/1005006358455017.html)  
  (Thickness: 1.4 mm. **The gold-plated version is highly recommended, the raw steel is almost impossible to solder**)

---

## Printed Parts
- Case in PLA
- Clip in PLA
- Plug in 95A TPU (optional)

---

## Printing Tips
(Tested on Prusa Core One and Bambulab H2D and A1)
- 0.4 mm nozzle
- 0.1 mm layer height
- 15% infill
- Supports only on build plate
- Support overhang angle below 45° (only the strap loops and the upper part of the USB port should be supported)

<img src="https://github.com/tommaier123/FlatShocker/blob/main/Pictures/Slice.png" height="200"/>

**Optional:**
- Concentric bottom layer looks nice
- Satin or smooth build plate

---

## Assembly Instructions
1. Gently file the top of the USB port hole where the support was attached. Check fit with the USB port **from the outside** until it just fits
2. Insert the USB port from the inside. The solder pins should go up and the resistors down (you will need a bit of force)
3. Move the USB port all the way back and secure it from the inside using the 3D-printed clip
4. (Optional) put in the TPU plug from the outside
5. Take the PCB and gently remove the battery
6. (Optional) for safety desolder the battery
7. Desolder both springs originally used for charging. If you have trouble desoldering the big one you can alternatively cut it
8. Connect thin wires (e.g. 30AWG for wire wrapping) to the pins where the springs were connected and feed them through the hole in the PCB
9. Check polarity (see picture): the big spring was negative and the small spring positive

    <img src="https://github.com/tommaier123/FlatShocker/blob/main/Pictures/PowerConnection.jpg" height="150"/>

10. Connect to the USB port accordingly. The outer small gold contact on the side marked with **V** is positive
11. Solder thicker wires (e.g. 22AWG) to the stainless steel discs. Keep the solder spot as thin as possible

    (I had some problems with flux, so I first put solder on the soldering tip, waited for the flux to burn off, then applied it to the disc. Don't sand the disc before soldering.)

12. Put the wires through the electrode holes and solder them directly to the shocker contacts (no need to desolder them)
13. Put the electrodes in their holes and arrange the wires so the vibrator can spin freely
14. Bend the antenna to clear the USB port and assemble the case to test if everything fits
15. Glue in the electrode discs from the inside using thin super glue

    <img src="https://github.com/tommaier123/FlatShocker/blob/main/Pictures/InternalOverview.jpg" height="250"/>
    
16. Screw the case together
17. **Enjoy** 😸

---

## Contact

Discord: Nova_Max

## Commercial Use
If you plan to use this design or any part of it for **commercial purposes**, please **contact me first**
