+++
alwaysopen = false
title = 'Uploading Files'
date = 2024-05-08T09:34:44-04:00
draft = true
+++

---

To upload files to the Ultimaker first get the stl, obj, or other 3D file type and open it with **UltiMaker Cura** either through opening through File Explorer or dragging the file into the **Ultimaker Cura** application. 

Picture

Once the file loads in, you can move it around the buildplate and change it to your likings, or upload more files by dragging them into the application window

### Moving

To move the print around the print bed, first click the item you wish to move, then click the (icon) icon and you will see three arrows pop up around your shape

picture

Once that happens you can either move it on the main axis by dragging those arrows, or just grab and drag the object to wherever you want it. 

You can also set it's exact position with the menu that appears next to the (icon) icon.

picture

there you will also see two checkboxes, *Lock Model* and *Drop Down Model*

*Lock Model* makes it so the model cannot move other than by changing the numbers in the menu, dragging the model or arrows will no longer move it 

*Drop Down Model* makes it so the model automatically moves it's lowest point to be touching the print bed, and it cannot be moved upwards, but can still be moved downwards. Keep in mind that anything shown below the print bed will not be printed.

It is reccomended to keep the *Lock Model* unselected and *Drop Down Model* selected

### Scaling

To scale your object, select the object, then select the (icon) icon, and three lines with boxes will appear. 

Picture

You can grab any of the three to stretch the object in the direction of that line, or instead grab the central box to stratch in all directions equally. 

Again a menu will pop up with certain options. The text boxes allow you to set the length, width, or height of the object by measured size or percentage of the original model.

picture

there you will also see two checkboxes, *Snap Scaling* and *Uniform Scaling* as well as a rewind icon

*Snap Scaling* makes it so the object will snap between set sizes

*Uniform Scaling* makes it so all the axis will scale uniformly, mneaning any change to one axis will be matched in the other two to keep the proportions of the object the same

The rewind icon will set the object to it's original dimentions

It is reccomended to keep the *Snap Scaling* unselected and *Uniform Scaling* selected unless you intentionally want a off proportion model

### Rotation

To scale your object, select the object, then select the (icon) icon, and three rings will appear.

picture

You can grab these rings and rotate them to rotate the object how you would like it to print. Keep in mind where the back of the bed is, signified by the lip where it is written *Ultimaker S5*. 

It is reccomended to rotate the object so that the least amount of overhang is acheived:

image

And the maximum amount of the print is touching the build plate, shown by the light blue highlight:

image

Again a menu with certain options will also appear next to the (icon) icon

Picture

The rewind icon will return the object to it's original orientation

the (icon) icon will rotate the model as little as possible to ensure a flat surface is laying against the print bed.

the (icon) icon will allow you to click on a face of the print and the program will lay it flat against the print bed. This feature is somewhat inconsistent so it may take a few tries to correctly allign it

*Snap Rotation* makes it so the print will only rotate in multiples of 15 degrees.

It is recoomended to keep *Snap Rotation* selected unless a particular angle is needed.

### Mirroring

When you select the (icon) icon, 6 arrows will appear. 

Picture

Clicking any of these arrows will mirror the object as if there was a mirror that the arrow was pointed directly into

### Mesh Type

This section will allow you to change how the object prints.

The first icon is the default, and will follow the print settings that you set.

The second prints as if is is support for a different model, which will follow the support settings that you set

The third will deal with overlapping objects, which is much more complicated, and a full desciprion of the options can be found here: link https://support.makerbot.com/s/article/1667417981430

The last will remove all supports in the volume of the object, but will not print the object itself

### Support blocking

The (icon) icon will block support in a cubic area, similar to the last option of the last tool

To use this, click the model you want to remove supports from, click the (icon) icon, and then click where you want the blocker. You can then edit the blocker as if it was any other object, using the tools above. The print will not generate any supports in the area of this block.

### Material selection

The Ultimaker can print two materials in the same print, simply click the object and select which of the two extruders you wish to print from.

## Done?

Once you are happy with the object's placement, move to the print settings section.





