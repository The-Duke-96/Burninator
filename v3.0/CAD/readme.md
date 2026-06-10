# CAD Files

- Use these files if you wish to modify something.  
- Keep in mind that the fan duct must blow air to the correct area: the tip of the hotend nozzle should sit about 2 mm beneath the lowest part of the cowl.  
- `backplate_base` and `MGNxH_carriage` are base bodies you can use to build upon.
- Extruder mounting holes and the ECAS adapter are present as a negative bodies that needs to be cut out.  
- I made use of custom parameters you can use to adapt the toolhead to almost any hotend:  
  - `hotend_length`: Lengthens the cowl to your hotend size.
  - `hotend_screwhole_radius`: Adjusts the hotend mounting holes.
  - `DS_adapter_length`: Shortens or lengthens the adapter to fit your existing DraftShift docks.
  - `extruder_screwholes_left`: Adjusts the center distance for the left extruder mounting hole.
  - `extruder_screwholes_right`: Adjusts the center distance for the right extruder mounting hole.
- I also provided a convenient Python export script that I use. It changes the parameters, makes the cuts, and exports all the files.  

**Note:** 
The Python script was written with the help of AI. 
I'm way too stupid to do it myself, so I claim absolutely no credit for it. 
All credit goes to those, which training data were used.