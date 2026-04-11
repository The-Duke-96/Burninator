# Burninator v2.2 💪🐉🔥
This toolhead is yet another 4010 toolhead, heavily inspired by the [Dragonburner](https://github.com/chirpy2605/voron/tree/main/V0/Dragon_Burner) and the [A4T](https://github.com/Armchair-Heavy-Industries/A4T/tree/main), all props to them.  
Thanks to Reddit user pd1zzle for suggesting the toolhead name, I really took a liking to it.  
Thanks to Reddit user linuxgangster for suggesting, testing, and providing feedback for the MadMax toolchanger adaptation.
And thanks to anyone, gave any suggestions, feedback, sharing or contributing usermods.
 
<p>
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/toolhead_render.png" width="300" height="400"> 
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/toolhead.jpg" width="300" height="400">
</p>
<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/final.jpg" width="600" height="900">

## But why?  
I created this toolhead because I wasn’t quite happy with the current toolhead options for my Stealthchanger.
Therefore, I decided to create my own toolhead to suit my use case and my printer.
I took features from the Dragonburner and the A4T and put them together, resulting in the Burninator.

## What its features?
It is small, smaller than the already compact Dragonburner, yet it can hold a UHF hotend, in my case the Dropeffect Next G Fiber with the UHF adapter, without missing out on nozzle and logo LEDs.
A monolithic cowl like the A4T cuts down the number of printed parts, screws, and heat inserts, increases rigidity, and simplifies assembly and disassembly.
Having a wall thickness of 1.2 mm makes the cowl more robust.  
It also adopts the A4Ts backflow inhibitor for decent part cooling performance.  

<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/Burninator_v2_CFD-img.png" width="1200" height="400">

## Hotend compatibility:
- For the SF cowl, any Pheatus Dragon like hotends should fit i.e.: NextG, TZ.
- For the UHF cowl, any Pheatus Dragon UHF like hotend should fit i.e.: NextG UHF, Rapido HF, Dragon ACE (with the spacer)
- The CHC-XL got it own cowls 
- Rapido UHF got it own cowls

## Anything else?  
Besides the Rapido UHF, CHC-XL, UHF and SF toolheads, there are: 
- MGN12H invertable (Voron-2 / Monolith Gantry mod), MGN9H (pandora's gantry mod) and MGN7H (Voron-0) carriage, with x-endstop and both, klicky or Beacon/Cartographer(+spacer) mount, for standalone, non-toolchanger printers 
- StealthChanger toolchanger: backplate, ajustable docks with inbuild PTFE whiper and spring steel blocker, adapter for DraftShft docks
- MadMax toolchanger: backplate, docks with inbuild spring steel blocker and optinal PTFE whiper, modified SF and UHF cowls to work with MadMax.

<img src="https://github.com/The-Duke-96/Burninator/blob/main/Images/render/full_render.png" width="1200" height="800">

## What is planed?
As discussed on [reddit](https://www.reddit.com/r/VORONDesign/comments/1rx1uao/advice_needed_about_the_burninator_toolhead/), I am planning to rework my CAD files to keep the scope manageable and more efficient to work with, and to save me a ton of time.  
This will take a while, since I have more important stuff in my life queued up that needs to be done first.  
Of course, CAD files are available for you to modify to your needs, and if you want, you can contribute is as a [Usermod](https://github.com/The-Duke-96/Burninator/tree/main/Usermods)

## How to Assemble?
Here's the [BOM](https://github.com/The-Duke-96/Burninator/blob/main/BOM.md).      
Here's a handy-dandy [Assembly manual](https://github.com/The-Duke-96/Burninator/blob/main/Assembly%20Manual.md).   

## Disclaimer:
- It turns out that when using printed parts for the Z-joints, the toolhead might be so small that the carriage of the Z linear rail hits the bottom of the frame before the toolhead touches the print bed for probing or leveling, since I have used a CNC kit for those parts from the beginning, I didn’t notice or consider it, a simple workaround is to add taller spacers or washers beneath the print bed, or use a diffrent, shorter Z-joints.
- Because the dock is quite small and space-saving, when using a door buffer for the StealthChanger, the DraftShift_dock_adapter needs to be used, otherwise the shuttle won’t reach the toolheads.
- If you use Beacon/Cartographer on CHC-XL or Rapido-UHF cowl, you need to extend the spacers to the correct lenght.
- StealthChanger and MadMax docks are designed for the SF and UHF cowls. I do not plan to adapt them for CHC XL or Rapido UHF, simply because a toolchanger already sacrifices print volume, and the smaller SF and UHF cowls are better suited for that use case. 
- For many files I have not received any feedback and, or could not test them myself, so if something is not working or not fitting, please let me know.
- Stock StealthChanger pickup and dropoff paths should work just fine, it might need some adjusment for the nozzle to scrub over the whiper.  If you like, you can use my custom paths:

```
params_dropoff_path: [{'y': 25, 'z':3}, {'y': 5, 'z':3} , {'y':0, 'z':3, 'f':0.5}, {'y':0, 'z':0, 'f':0.5}, {'y':0, 'z':-10}]
params_pickup_path: [{'y':0, 'z':-10}, {'y':0, 'z':0, 'f':0.5, 'verify':1}, {'y':0, 'z':3, 'f':0.5}, {'y': 25, 'z':3}]
```

## Support:
<a href="https://ko-fi.com/theduke96">
  <img src="https://ko-fi.com/img/githubbutton_sm.svg"
       alt="Support this project"
       width="400" />
</a>
