# Flat Shocker

This project aims to improve OpenShock shockers by replacing the stock electrodes that are designed for dogs, not humans.  
By using a custom 3D-printed bottom case, we remove the need for a spacer, making the shocker flatter and more comfortable.

<img src="https://github.com/tommaier123/FlatShocker/blob/main/Pictures/FlatShocker.jpg" height="200"/> <img src="https://github.com/tommaier123/FlatShocker/blob/main/Pictures/HeightComparison.jpg" height="200"/> <img src="https://github.com/tommaier123/FlatShocker/blob/main/Pictures/Top.jpg" height="200"/>

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

## Optional Top
- Print the top for a fully customized shocker
- There are two versions: the standard one and one with an embossed lightning bolt for the LEDs. How it looks depends a lot on the material. If its too translucent everything glows and if it's too opaque you don't see anything
- You may use the rubber gasket from the original top but it's probably not necessary
- The top is fully compatible with the stock bottom. So you can also use it without having a FlatShocker

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
- Support overhang angle below 30° (only the strap loops and the upper part of the USB port should be supported)

<img src="https://github.com/tommaier123/FlatShocker/blob/main/Pictures/Slice.png" height="200"/>

**Optional:**
- Concentric bottom layer looks nice
- Satin or smooth build plate
---

## Assembly Instructions
1. Gently file the top of the USB port hole where the support was attached. Check fit with the USB port **from the outside** until it just fits
2. (Optional) put in the TPU plug from the outside
3. Solder two thin wires (e.g. 30AWG for wire wrapping) to the USB port, the gold contact next to **V** is positive, you can use either of the negative pins
   
  <img src="https://github.com/tommaier123/FlatShocker/blob/main/Pictures/USBC.png" height="150"/>
  
4. Solder thicker wires (e.g. 22AWG) to the stainless steel discs. Keep the solder spot as thin as possible. Following are some tips to make it easier:
   - Clean the discs with alcohol (ethanol, isopropanol)
   - Don't sand the discs
   - Put them on a heat resistant surface (cardboard)
   - Use leaded solder (Optional)
   - Put solder on the iron and let the flux burn off
   - Place the soldering iron on the disc without moving until the solder starts to wet the disc
   - Move the tip to spread it thinly
   - Once this is done immediately remove the soldering iron
   - Now you can solder the pre-tinned wires to the solder spots on the discs
5. Disassemble the shocker
6. Take out the PCB and gently remove the battery
7. Desolder the battery for safety
8. Desolder both springs originally used for charging. If you have trouble desoldering the big one you can alternatively cut it
9. Feed the USB port wires through the hole in the PCB and solder them to the pins where the springs were connected. (You can leave the cables a bit longer for easier handling)
    
    <img src="https://github.com/tommaier123/FlatShocker/blob/main/Pictures/PowerConnection.jpg" height="150"/>
    
10. Check polarity (see picture): the big spring was negative and the small spring positive
11. Insert the USB port into the case from the inside. The solder pins should go up and the resistors down (you will need a bit of force)
12. Move the USB port all the way back and secure it from the inside using the 3D-printed clip
13. Put the disc wires through the electrode holes and solder them directly to the shocker contacts (no need to desolder them) (trim the wires short, they can get in the way during assembly otherwise)
14. Solder the battery back where it was. **It beeps when you reconnect it**
15. Put the electrodes in their holes and arrange the wires so the vibrator can spin freely and the button is not blocked
16. Bend the antenna to clear the USB port and assemble the case to test if everything fits
17. Test if the schocker charges through the USB port
18. Glue in the electrode discs from the inside using thin super glue

    <img src="https://github.com/tommaier123/FlatShocker/blob/main/Pictures/InternalOverview.jpg" height="250"/>
    
19. Screw the case together
20. **Enjoy** 😸

---

## Contact

Discord: Nova_Max

## Commercial Use
If you plan to use this design or any part of it for **commercial purposes**, please **contact me first**
