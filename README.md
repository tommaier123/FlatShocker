# Flat Shocker

This project aims to improve OpenShock shockers by replacing the stock electrodes that are designed for dogs, not humans.  
By using a custom 3D-printed bottom case, we remove the need for a spacer, making the shocker flatter and more comfortable.

<img src="https://github.com/tommaier123/FlatShocker/blob/main/Pictures/FlatShocker.jpg" height="200"/> <img src="https://github.com/tommaier123/FlatShocker/blob/main/Pictures/HeightComparison.jpg" height="200"/>

---

## What You Gain by Doing This Modification
- Decrease total shocker height by 1.3 cm
- USB-C charging
- Color customization

## What You Keep
- Full functionality including Shock, Vibrate, and Beep
- Same shocker strength (if not slightly stronger)

## What You Lose
- Water tightness. But it's still water resistant - just don't go swimming with it

---

## Bill of Materials
- 1× USB-C port [AliExpress link](https://de.aliexpress.com/item/1005008942189266.html) (There are two versions, both work)

  <img src="https://github.com/tommaier123/FlatShocker/blob/main/Pictures/USBC.png" height="150"/>
- 2× 15 mm stainless steel discs [AliExpress link](https://de.aliexpress.com/item/1005006358455017.html)  
  (Thickness: 1.4 mm. Both stainless steel and gold-plated versions work, gold-plated may be better for skin contact)

---

## Printed Parts
- Case in PLA
- Clip in PLA
- Plug in 95A TPU (optional)

---

## Printing Tips
(Tested on Prusa Core One and Bambulab H2D)
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
1. Gently sand the top of the USB port hole where the support was attached. Check fit with the USB port **from the outside** until it just fits
2. Insert the USB port from the inside. The solder pins should go up and the resistors down (you will need a bit of force)
3. Move the USB port all the way back and secure it from the inside using the 3D-printed clip
4. (Optional) put in the TPU plug from the outside
5. Take the PCB and gently remove the battery
6. Desolder both springs originally used for charging
7. Connect thin wires to the pins where the springs were connected and feed them through the hole in the PCB
8. Check polarity using a multimeter: the big spring was negative and the small spring positive
9. Connect to the USB port accordingly. The outer small gold contact on the side marked with **V** is positive
10. (Optional) lightly sand the top side of the discs for better soldering and glue adhesion (might be unnecessary)
11. Solder thicker wires to the stainless steel discs

    (I had some problems with flux, so I first put solder on the soldering tip, waited for the flux to burn off, then applied it to the disc)
12. Put the wires through the electrode holes and solder them directly to the shocker contacts (no need to desolder them)
13. Put the electrodes in their holes and arrange the wires so the vibrator can spin freely
15. Bend the antenna to clear the USB port and assemble the case to test if everything fits
17. Glue in the electrode discs from the inside using thin super glue
18. Screw the case together
19. **Enjoy** 😸

---

## Commercial Use
If you plan to use this design or any part of it for **commercial purposes**, please **contact me first**
