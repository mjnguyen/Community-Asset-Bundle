Phoenix Hawk
version 2018-09-30 21:30

Original Phoenix Hawk models & textures created by Pirana Games for MechWarrior Online 
All other models, textures, sounds, and assets created by Harebrained Schemes for BATTLETECH
Assets merged and (slightly) modified by SolahmaJoe solely for use in HBS's BATTLETECH

Current Release:
  Body models (including) rescaled & imported
  Textures adjusted from PGI assets.
  Weapons: 
	L/R Arm Side & gunpod PPC
	L/R Arm Side & gunpod Lasers
    L/R Arm Underside of Forearm Flamer, Laser, MG (AP Weapons)
    Center Torso Flamer, Laser, MG (AP Weapons)
    Right Torso PPC, Laser, Flamer (1 mount)

Note on arm mounts:
  The first/top most weapon arm laser or ppc will appear in the forearm side mount point.
  The second will appear in the handheld gunpod.
  (This is swapped from the original PGI models.)
  I decided to organize the arm mounts due to how HBS's code mounts weapon models.
  There is no way to specify the mount point via the json file, it's decided at mission load.
  Because all the stock Phoenix Hawk models have a Medium Laser in each arm and a Large Laser in just the right
  I put the ML first so they both get _eh1 side mount, and the LL second to get _eh2 gunpod.
  This results in the Large Laser appearing in the RA gunpod and both Medium Lasers in the side mounts.
  Otherwise the LA Medium Laser would always get mounted to the gunpod, which just seems weird.

Known Issues:
  Jump Jet effects not playing (involves weird conflict with SimGame prefab)
  Searchlight don't get mounted (same problem as jump jets)
  Clavicle & hip models are not aligned correctly (hidden inside other models)
  Pelvis alignment is slightly off (got tired of fighting with it)
    
Install:
  Install BTML and ModTek (https://github.com/Mpstark/ModTek/wiki/The-Drop-Dead-Simple-Guide-to-Installing-BTML-&-ModTek-&-ModTek-mods)
  Drag folder into BATTLETECH\Mods\
  
