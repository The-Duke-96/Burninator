Direct replacement of PTFE tubing wiper in favor of a silicone wiper. 

This is designed to be a bit tight of a fit into the existing PTFE slot. No modifications to the dock itself but you have have to snap them into place. The wiper used [is these that are common on the A1 printers](https://a.co/d/09I6NoFP) so they are available from all over the place. They are trimmed down to about 4 rows and slide into place from one side. The ones i had have some glue on the bottom with a peel off strip to expose it. I would imagine most do but a drop of glue would work too if needed. 

The print should be with the Nozzle wiper portion facing up. Some support of whatever flavor you like on the bottom, it's a super fast print so it's easy enough to do some testing with what works for your setup.

When installing put the short overhang side out toward the shuttle and the 45 degree slash in toward the dock body. If you insert backwards the pin slots ont he dock will catch when grabbing/dropping off and make funny noises. 

<p align="center">
  <img src="./model view.jpg" alt="Dock wiper">
</p>

<p align="center">
  <img src="./Front View.jpg" alt="Front View" width="250">
  <img src="./View with docked.jpg" alt="Back View" width="250">

The original docking params may need to be adjusted for the wiper similar to the adjustments made for the PTFE tube version. 

The magic values to get a little wipe on the way in and on the way out is the First Z on drop off and the last Z on pickup. I changed them both from 4 to 2 (based on the original Easy-tool-changer repo numbers so it wipes directly across the silicone pad instead of coming up high just across the top of the wiper. 

```
params_dropoff_path: [{'y':9.5 ,'z':2}, {'y':9.5, 'z':2}, {'y':5.5, 'z':0}, {'z':0, 'y':0, 'f':0.5}, {'z':-10, 'y':0}, {'z':-10, 'y':16}]
params_pickup_path: [{'z':-10, 'y':16}, {'z':-10, 'y':0}, {'z':0, 'y':0, 'f':0.5, 'verify':1}, {'y':5.5, 'z':0}, {'y':9.5, 'z':2}, {'y':9.5 ,'z':2}]
```

In order to tune this the Dock_Tuner Macros work great to come at them slowly and test your height requirements with minimal carnage. 