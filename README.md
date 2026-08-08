# Burninator v3.0 💪🐉🔥
This toolhead is yet another 4010 toolhead, heavily inspired by the [Dragonburner](https://github.com/chirpy2605/voron/tree/main/V0/Dragon_Burner) and the [A4T](https://github.com/Armchair-Heavy-Industries/A4T/tree/main), all props to them.  
Thanks to Reddit user pd1zzle for suggesting the toolhead name, I really took a liking to it.  
Thanks to Reddit user linuxgangster for suggesting, testing, and providing feedback for the MadMax toolchanger adaptation.  
And thanks to anyone, who gave any suggestions, gave feedback, was sharing or contributing usermods.
 
<p>
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/toolhead_render.png" width="300" height="400"> 
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/toolhead.jpg" width="300" height="400">
</p>
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/final.jpg" width="600" height="900">

## But why?  
I created this toolhead because I wasn’t quite happy with the current toolhead options for my Stealthchanger.
After some testing, I decided to create my own toolhead to suit my use case and my printer.
I took features from the Dragonburner and the A4T and put them together, resulting in the Burninator.

## Features:
- Very small and compact, yet fits UHF hotends
- Monolithic cowl design
- Easy assembly and disassembly
- Stronger, 1.2 mm thick walls
- CFM optimized cooling and A4T's backflow inhibitors
- MGN12H, MGN9H, and MGN7H carriages compatible with up to 10 mm belts
- MGN12H and MGN9H carriages also compatible with the [Monolith_Gantry](https://github.com/Monolith3D/Monolith_Gantry) mod
- MGN12H also compatible with Tridex (6mm belts)
- StealthChanger ready
- MadMax ready

<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/Burninator_v2_CFD-img.png" width="1200" height="400">
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/overview.png" width="1050" height="580">

## Compatibility:

**Hotends:** 
- Any top-mounted, Phaetus-style hotend
- SF: Dragon, NextG, TZ, etc.
- UHF: Dragon UHF, NextG UHF, Rapido HF, Dragon ACE (with spacer)
- Rapido UHF
- CHC-XL (+MZE)

**Extruders:**
- Orbiter / Galileo 2
- Sherpa Mini
- Sherpa Micro
- ECAS / Bowden
- LGX & LGX Lite (using the `LGX_adapter`)
- Or similar

**Note:**
- Using the custom parameters in Autodesk Fusion 360, you can adapt the design to almost any Phaetus-style, top-mounted hotend and extruder.

## What is planned?
Waiting for user feedback, opened issues, and suggestions or recommendations. I might also test out some ideas for potential future versions. Other than that, not much for now.  
Of course, CAD files are available for you to modify to your needs, and if you want, you can contribute is as a [Usermod](https://github.com/The-Duke-96/Burninator/tree/main/Usermods)

## How to Assemble?
Here's the [BOM](https://github.com/The-Duke-96/Burninator/blob/main/BOM.md).      
Here's a handy-dandy [Assembly manual](https://github.com/The-Duke-96/Burninator/blob/main/Assembly%20Manual.md).   

## Disclaimer:
- **Z-Axis Clearance:** If you use printed Z-joints, the toolhead's compact size might cause the Z-rail carriage to hit the frame before the nozzle touches the bed. Workaround: Add taller spacers under the print bed or use shorter Z-joints.  
- **StealthChanger Door Buffer:** If using a door buffer, the `DraftShift_dock_adapter` is required, otherwise the shuttle cannot reach the toolhead.  
- **Sensor Mounts:** Ensure the `beacon/cartographer_spacer`, or `klicky_mount` is scaled in the Z-axis to fit your specific setup.  
- **Beta Files:** Some files are untested by me. If anything does not fit or work as expected, please open an issue or let me know.
- **Macro Adjustments:** Stock StealthChanger pickup and dropoff paths work, but you might need slight adjustments for the nozzle to properly scrub the wiper.  

```
params_dropoff_path: [{'y': 25, 'z':6.5}, {'y': 5, 'z':6.5} , {'y':0, 'z':6.5, 'f':0.5}, {'y':0, 'z':0, 'f':0.5}, {'y':0, 'z':-10}]
params_pickup_path: [{'y':0, 'z':-10}, {'y':0, 'z':0, 'f':0.5, 'verify':1}, {'y':0, 'z':6.5, 'f':0.5}, {'y': 25, 'z':6.5}]
```

## Support:
<a href="https://ko-fi.com/theduke96">
  <img src="https://ko-fi.com/img/githubbutton_sm.svg"
       alt="Support this project"
       width="400" />
</a>
