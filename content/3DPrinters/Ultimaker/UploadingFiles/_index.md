+++
alwaysopen = false
title = 'Uploading Files'
date = 2024-05-08T09:34:44-04:00
draft = false
weight = 1
+++

---

To upload files to the Ultimaker first get the stl, obj, or other 3D file type and open it with **UltiMaker Cura** either through opening through File Explorer or dragging the file into the **UltiMaker Cura** application. 

![image](/images/113.PNG) 

Once the file loads in, you can move it around the buildplate and change it to your likings, or upload more files by dragging them into the application window

![image](/images/114.PNG)

### Moving

To move the print around the print bed, first click the item you wish to move, then click the (![icon](/images/115.PNG)) icon and you will see three arrows pop up around your shape

![image](/images/116.PNG)

Once that happens you can either move it on the main axis by dragging those arrows, or just grab and drag the object to wherever you want it. 

You can also set it's exact position with the menu that appears next to the (![icon](/images/115.PNG)) icon.

![image](/images/118.PNG)

There you will also see two checkboxes, `Lock Model` and `Drop Down Model`

`Lock Model` makes it so the model cannot move other than by changing the numbers in the menu, dragging the model or arrows will no longer move it 

`Drop Down Model` makes it so the model automatically moves its lowest point to be touching the print bed, and it cannot be moved upwards, but can still be moved downwards. Keep in mind that anything shown below the print bed will not be printed.

It is recommended to keep the `Lock Model` unselected and `Drop Down Model` selected

### Scaling

To scale your object, select the object, then select the (![icon](/images/119.PNG)) icon, and three lines with boxes will appear. 

![image](/images/120.PNG)

You can grab any of the three to stretch the object in the direction of that line, or instead grab the central box to stretch in all directions equally. 

Again a menu will pop up with certain options. The text boxes allow you to set the length, width, or height of the object by measured size or percentage of the original model.

![image](/images/121.PNG)

There you will also see two checkboxes, `Snap Scaling` and `Uniform Scaling` as well as a rewind icon

`Snap Scaling` makes it so the object will snap between set sizes

`Uniform Scaling` makes it so all the axes will scale uniformly, meaning any change to one axis will be matched in the other two to keep the proportions of the object the same

The rewind icon will set the object to its original dimensions

It is recommended to keep the `Snap Scaling` unselected and `Uniform Scaling` selected unless you intentionally want an of proportion model

### Rotation

To scale your object, select the object, then select the (![icon](/images/122.PNG)) icon, and three rings will appear.

![image](/images/123.PNG)

You can grab these rings and rotate them to rotate the object how you would like it to print. Keep in mind where the back of the bed is, signified by the lip where it is written `Ultimaker S5`. 

It is recommended to rotate the object so that the least amount of overhang is achieved:

![image](/images/124.png)

And the maximum amount of the print is touching the build plate, shown by the light blue highlight:

![image](/images/125.png)

Again a menu with certain options will also appear next to the (![icon](/images/122.PNG)) icon

![image](/images/126.PNG)

The rewind icon will return the object to its original orientation

The (![icon](/images/127.PNG)) icon will rotate the model as little as possible to ensure a flat surface is laying against the print bed.

The (![icon](/images/128.PNG)) icon will allow you to click on a face of the print and the program will lay it flat against the print bed. This feature is somewhat inconsistent so it may take a few tries to correctly align it

`Snap Rotation` makes it so the print will only rotate in multiples of 15 degrees.

It is recommended to keep `Snap Rotation` selected unless a particular angle is needed.

### Mirroring

When you select the (![icon](/images/129.PNG)) icon, 6 arrows will appear. 

![image](/images/130.PNG)

Clicking any of these arrows will mirror the object as if there was a mirror that the arrow was pointed directly into

### Mesh Type

When you click the (![icon](/images/131.PNG)) icon, a section will open that allows you to change how the object prints.

![image](/images/132.PNG)

The first icon is the default, and will follow the print settings that you set.

The second prints as if is is support for a different model, which will follow the support settings that you set

The third will deal with overlapping objects, which is much more complicated, and a full description of the options can be found here: link https://support.makerbot.com/s/article/1667417981430

The last will remove all supports in the volume of the object, but will not print the object itself

### Support Blocking

The (![icon](/images/133.PNG)) icon will block support in a cubic area, similar to the last option of the last tool

To use this, click the model you want to remove supports from, click the (![icon](/images/133.PNG)) icon, and then click where you want the blocker. You can then edit the blocker as if it was any other object, using the tools above. The print will not generate any supports in the area of this block.

### Material Selection

The Ultimaker can print two materials in the same print, simply click the object and select which of the two extruders you wish to print from.

## Done?

Once you are happy with the object's placement, move to the print settings section.





