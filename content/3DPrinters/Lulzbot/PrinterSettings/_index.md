+++
alwaysopen = false
title = 'PrinterSettings'
date = 2024-05-08T09:33:28-04:00
draft = true
+++

Once you have your object oriented as desired, select your material

## Material selection

At the top of the display there will be a dropdown menu to select material type.

Image 

Click to show the options for material selection and select the one currently loaded in the printer.

## Print Settings

Now move to the print settings menu. There you will see lots of options, which I will briefly review here 

Image

### Profiles

Firstly you will see a list of **Profiles**. These are the easiest way to select your settings.

image

*High Detail* prioritizes details and fucntionality. Use this for projects that need to look good or mechanically function.

*Standard* Is a mix of detail and speed. Use this for general printing.

*High Speed* is for quickly printing models that are prototypes or not particularly valuable. Use this for testing and quick prints.

### Other Settings

There are lots of other settings that can be adapted, we will breifly review the most important

#### Infill

##### Infill Density

Int the infill section, the *Infill Density* dropdown will allow you to dictate how much of the interior of the print is filled in, with 0 meaning no fill, and 100 meaning completely full

image

anything down to *10%* will be self supporting enough, although *20%* is reccomended for nearly every print. *70%* is the absolute maximum you need to go for a high strength print, however this should only be used if extreme strength is needed.

##### Infill pattern

This allows for a selection of how the infill will be created, and the options are shown below:

Grid
Lines
Triangles
Trihexagon
Cubic
Cubic Subdivision
Octet
Quarter Cubic
Concentric
Zig Zag
Cross
Cross 3d
Gyroid
Lightning

__ is the reccomended setting but this choice has little effect on the overall print.

#### Support 

Supports are how the printer helps overhangs print, as the printer must always work from bottom to top and cannot print without a surface to print on. Support can be selected and deselected, but is reccomended to use whenever there are overhangs or floating objects in your print

##### Support Structure

This box allows for two choices, *Normal* and *Tree*

*Normal* creates sheets of support under your print, connected at top and bottom:

image

*Tree* creates branching circular structures to support overhangs in the model:

image

*Normal* is the reccomended setting unless it creates particularly hard to remove sections with print trapped between support on all sides

##### Support Placement

Placement designates where supports generate, and gives two options, *Everywhere* and *Touching Buildplate*

*Everywhere* means any overhang will be supported, no matter where on the print it is.

*Touching Buildplate* will only support overhangs over the buildplate, and overhangs that have other bits of object below will not generate support

It is reccomended to use *Everywhere* when overhangs are present.

#### Custom settings

Many other specific settings can be tuned however there are far too many to cover in this guide, so look to a more specific guide on the Cura LulzBot Edition Slicer for information on that.

## Done?

Once you have your preferred settings set, move to the slicing files section