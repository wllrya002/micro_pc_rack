# Micro pc rack
I needed a micro pc rack to house a small proxmox cluster at home.

## Credit to...
Thanks to **Athers3d** from **MakerWorld** for the original design, [site](https://makerworld.com/en/models/472809-dell-optiplex-micro-storage-rack#profileId-778791). If the webpage isnt available have a look in the repo for the [printed webpage](https://github.com/wllrya002/micro_pc_rack/blob/main/docs/Dell%20Optiplex%20Micro%20Storage%20Rack%20by%20Athers3d%20-%20MakerWorld.pdf).

## Manipulations
The original stl files were adjusted to fit onto a Wanhao i3 duplicator. I ended up doing the following:
 - Shortened the back cable extended pieces to fit into my build area of the Wanhao i3 duplicator (200 x 200 x 180mm -> w x d x h)
 - Added a central support to both left and right segments. The thought behind this was that the original cable extended pieces also provided some structural support, so by removing these I wanted to add support elsewhere.
 - Changed infill from 20 to 40% for side pieces.

Below is an example of the before and after cases...top one is the original right piece, bottom is the shortened version with the structural section down the centre.

[]()

## Software used
 - Quick viewing and adding the left and right side support beams using Sketchup Make (version 17.2.2555).
 - Plane slicing off the back cable extended pieces using Autocad MeshMixer (version 3.5.474).
 - Changing the infill, slicing and exporting the gcode with UltiMaker Cura (version 5.9.0).
