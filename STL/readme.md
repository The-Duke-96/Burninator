# STL Files

- All printed parts are already oriented correctly for printing.
- Required print supports are built in.
- Cosmetics and their corresponding parts must be printed together, just align them and decide if and how you want to color them.
- For the LED diffuser, it's recommended to print it in white or clear filament. You can also leave out the logo LED and print it in any color you want.

---

# Assembly Manual

- Start by installing the heat inserts: two in the bottom rear, two on top of the cowl, two at the top of either the StealthChanger backplate or the MGN12H carriage, two in the back of the EBB mount, one in the bottom of the dock, and two M5 inserts in the dock adapter.

<p>
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/cowl_heatinsert1.jpg" width="300" height="300"> 
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/cowl_heatinsert2.jpg" width="300" height="300">
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/backplate_heatinsert.jpg" width="300" height="300">
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/EBB_mount_heatinsert.jpg" width="300" height="300"> 
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/dock_heatinsert.jpg" width="300" height="300"> 
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/adapter_heatinsert.jpg" width="300" height="300"> 
</p>

- Insert the 2510 fan from the back and slide it upward, wedging it into place. The two small nubs should fit into the bottom holes of the fan, securing it further. This works the same way as on the Dragonburner.
- Insert the LED diffuser into the Voron logo cutout.

<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/insert diffuser_fan.jpg" width="300" height="300">

- Continue with soldering the LEDs. You'll need six pieces of 20mm wire and three pieces of 170mm wire.
- Solder the first three short wires to the OUT pads of the first LED.
- Solder the second LED, facing the opposite direction of the first.
- Solder the last three short wires to the second LED, facing the same direction as the first set.
- Solder the third LED so that it faces the same direction as the first LED and opposite the second.
- Solder the 170mm wire to the IN pads and crimp on the connector.  
  **Note:** Make sure the wires are soldered in the correct orientation as shown in the picture.
  
<p>
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/solder_led1.jpg" width="300" height="300">   
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/solder_led2.jpg" width="300" height="300">   
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/solder_led3.jpg" width="300" height="300">  
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/solder_led4.jpg" width="300" height="300"> 
</p>

- Insert the second LED into the LED carrier first, then the remaining two, it’s easier that way.
- Insert the LED carrier from the back, placing the bottom edge into the cowl ledge. Tilt it, then press it firmly into place. Ensure the diffuser is seated in the front groove of the LED carrier.

<p>
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/led_carrier.jpg" width="300" height="300">   
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/insert_ledcarrier.jpg" width="300" height="300">   
</p>

- For the 4010 fans: remove the front cover and glue in A4T’s Backflow Inhibitor (optional but recommended).
- One of the fans needs its wires bent toward the back. You may also resolder the wires.
- Slide the fans into the sides of the cowl, same as on the Dragonburner.

<p>
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/gluein_backflow.jpg" width="300" height="300">   
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/insert_fans.jpg" width="300" height="300">   
</p>

- Install the hotend. In my case, a Dropeffect NextG Fiber UHF is used. Ensure it's rotated correctly so the cables point toward the back corner.
- Route the thermistor wire with the cable sleeve to the opposite side, as it will not fit through the cowl and backplate cutouts. Route the heater wires on the other side, bending them so they will fit cleanly.

<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/insert_hotend.jpg" width="300" height="300">

- Place the backplate, wiggle the cables into position, and ensure the metal hose sits inside the backplate groove underneath the center hole. Screw it down.
- Install either M3x40 SHCS screws with a 3 mm spacer, or M3x35 SHCS screws without the spacer and place a 6×3 mm magnet on top.
- Route cables into the grooves and secure them with zip-ties.
- If using the StealthChanger backplate, install the OptoTap PCB.

<p>
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/insert_backscrews.jpg" width="300" height="300">   
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/cable_ziptie.jpg" width="300" height="300">   
</p>

- Install a 22 mm PTFE tube and mount your extruder. In this example, the Galileo 2 WristWatch is used, followed by the toolhead PCB.
- In this setup, the EBB36_G2WW_Mount is required due to interference from the OptoTap.
- The toolhead is now complete.

<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/toolhead_done.jpg" width="300" height="300">

---

# Cowl SF Assembly

- Assembling the SF cowl is only a little bit different from the UHF cowl.
- For soldering the LEDs, you need wires in the following lengths: 3 × 47 mm, 3 × 30 mm, and 3 × 170 mm.
- Start with the last LED and solder the 47 mm wires to the IN.
- Now solder the second LED, and then the first LED, using the 30 mm wires.
- Finally, solder the 170 mm wires and crimp on the connector.  
  **Note:** Make sure the wires are soldered in the correct orientation as shown in the picture.
- After that, place them into the LED carrier.

<p>
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/solder_SF_LED.jpg" width="300" height="300">
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/LED__SF_carrier.jpg" width="300" height="300">
</p>

- Moving on to the cowl: first insert the top LED carrier. The cable should exit sideways into the cable channel.

<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/insert_SF_topLED.jpg" width="300" height="300">

- Then tuck the cable into the corner and run it down along the wall. Push the larger LED carrier aside and insert the 2510 fan.
- After that, push the larger LED carrier into place.  
  **Note:** Due to the tight space, routing the cable and seating everything can be a bit tricky. The better the soldering job and the thinner the wires, the easier it gets.

<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/SF_LED_FAN_insert.jpg" width="300" height="300">


---

# Dock Assembly

- Insert the 31 mm spring steel blocker into the rear slit and secure it with an M3x5 screw.
- Take a 23 mm PTFE tube for the wiper, bend it in the middle, wedge it into the back holder, then press down to straighten it out.
- Press the magnets into the top.
- Mount the dock onto the crossbar, optionally using the adapter.

<p>
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/dock_blocker.jpg" width="300" height="300">   
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/dock_wiper.jpg" width="300" height="300">   
</p>




