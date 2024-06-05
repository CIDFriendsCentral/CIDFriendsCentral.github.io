+++
alwaysopen = false
title = 'Printer Settings'
date = 2024-05-08T09:33:28-04:00
draft = false
weight = 2
+++

---

Once you have your object oriented as desired, move to the print settings menu.

There you will see lots of options, which I will briefly review here 

![image](/images/134.PNG)

### Profiles

Firstly you will see a list of **Profiles**. These are the easiest way to select your settings.

`Balanced` strikes a balance of productivity, quality, strength, and accuracy. Use this for general projects.

`Visual` prioritizes the outwards appearance to optimize visual properties. Use this for projects that need to look good.

`Engineering` prioritizes accurate tolerances, and mechanical strength. Use this for projects will moving parts or that need to be stronger.

`Draft` is for models that are prototypes or not particularly valuable. Use this for testing and quick prints.

### Resolution

Resolution will change the thickness of every layer. The bigger each layer is the faster the model will print, but the worse it will look and function. It's recommended to use `Fine` for good visual quality or `Fast` for speed and basic functionality. 

Below it may say "Recommended settings for _____ were altered". Clicking the rewind icon will reset to recommended settings and the floppy disk icon will save the current settings as a new preset.

### Strength

##### Infill Density

This slider will allow you to dictate how much of the interior of the print is filled in, with 0 meaning no fill, and 100 meaning completely full

![image](/images/135.png)

anything down to `10%` will be self supporting enough, although `20%` is recommended for nearly every print. `70%` is the absolute maximum you need to go for a high strength print, however this should only be used if extreme strength is needed.

##### Infill Pattern

This allows for a selection of how the infill will be created, with options shown below:



Grid
![image](/images/136.1.PNG)
Lines
![image](/images/136.2.PNG)
Triangles
![image](/images/136.3.PNG)
Trihexagon
![image](/images/136.4.PNG)
Cubic
![image](/images/136.5.PNG)
Cubic Subdivision
![image](/images/136.6.PNG)
Octet
![image](/images/136.7.PNG)
Quarter Cubic
![image](/images/136.8.PNG)
Concentric
![image](/images/136.9.PNG)
Zig Zag
![image](/images/136.10.PNG)
Cross
![image](/images/136.11.PNG)
Cross 3d
![image](/images/136.12.PNG)
Gyroid
![image](/images/136.13.PNG)
Lightning
![image](/images/136.14.PNG)

Triangles is the recommended setting but this choice has little effect on the overall print.

##### Shell Thickness

This lets you set the thickness of the outer shells of the print, with the first box designating the side walls, and the second designating the top and bottom

### Support 

Supports are how the printer helps overhangs print, as the printer must always work from bottom to top and cannot print without a surface to print on. Support can be selected and deselected, but is recommended to use whenever there are overhangs or floating objects in your print

##### Support Type

This box allows for two choices, `Normal` and `Tree`

`Normal` creates sheets of support under your print, connected at top and bottom:

![image](/images/137.PNG)

`Tree` creates branching circular structures to support overhangs in the model:

![image](/images/138.PNG)

`Normal` is the recommended setting unless it creates particularly hard to remove sections with print trapped between support on all sides

##### Placement

Placement designates where supports generate, and gives two options, `Everywhere` and `Touching Buildplate`

`Everywhere` means any overhang will be supported, no matter where on the print it is.

`Touching Buildplate` will only support overhangs over the buildplate, and overhangs that have other bits of object below will not generate support

It is recommended to use `Everywhere` when overhangs are present.

### Adhesion

Adhesion helps prints stick to the print bed and avoid shifting and warping off of the bed. It is recommended to keep this setting selected for any print.

### Custom Settings

Many other specific settings can be tuned by clicking `Show Custom` however there are far too many to cover in this guide, so look to a more specific guide on the Cura Slicer for information on that

## Done?

Once you have your preferred settings set, move to the slicing files section

