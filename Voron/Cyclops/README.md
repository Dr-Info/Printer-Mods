# CYCLOPS
This is a modded version of stealthburner for a nozzle camera.

***Under construction therefore not finalized. Currently assessing pathway for OV5640 camera FC.***

### Printing
  * Default voron settings
  * No supports needed

### Camera Parts

Camera Module: https://www.aliexpress.us/item/3256803755405216.html?spm=a2g0o.order_list.0.0.722b1802TpJ9ZM&gatewayAdapt=glo2usa&_randl_shipto=US

Longer Camera: https://www.aliexpress.us/item/3256803202646762.html?spm=a2g0o.order_list.0.0.722b1802TpJ9ZM&gatewayAdapt=glo2usa&_randl_shipto=US

Longer Cable: https://www.aliexpress.us/item/3256803896166623.html?spm=a2g0o.order_list.0.0.722b1802TpJ9ZM&gatewayAdapt=glo2usa&_randl_shipto=US

***Note: I would advise sticking with the fixed focal cameras as the AF might have issues with focusing due to fast ptint moves. You will need at least a 78mm long cable. I used a 300mm cable for my 2.4 300^3 which has the Pi mounted at the front of the printer. My current setup is the OV5640 60 degree module replaced with a OV5640 68 degree 78mm camera and a 300mm cable to the Pi.***

Installation tips:
1. Run the the 5pin to USB with your bowden tube and secure it to prevent the cable from wondering during printing. Reason being the cable is made of PVC which isn't ideal for drag chains. If you plan to make your own cable and place in drag chain it needs to be shielded cable for the signal wires.
2. Adjust the focus and then place some clear nail polish or super glue to prevent loss focus.
3. Clean the lense periodically with IPA.

### BOM
**OV5640 PCB**
Size | Qty
--- | ---
M3x8 | 2
M2 Self Tap | 2

**OV5640 Camera**
Size | Qty
--- | ---
M3x6 | 1

![Cyclops](Images/ISO_MFL.jpg)

![Cyclops](Images/ISO_LFL.jpg)

![Cyclops](Images/ISO_LRL.jpg)
