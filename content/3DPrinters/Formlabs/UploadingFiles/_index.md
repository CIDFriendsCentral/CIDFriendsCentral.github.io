+++
alwaysopen = false
title = 'Uploading Files'
date = 2024-05-08T09:34:44-04:00
draft = false
weight = 1
+++

---

To upload files to the FormLabs printer first open the **PreForm** application.

![image](/images/1.PNG)

Then drag and drop your intended file into the work area of the window

![image](/images/2.PNG)

From here you have a few options about how to set up your print. 

### One Click Print

The simplest is to hit the (![icon](/images/3.PNG)) icon and use `One Click Print`

![image](/images/4.PNG)

Hit the {{% badge %}}Set Up Your Print{{% /badge %}} button and the app will automatically rotate your model and add supports for the best print generation. 

![image](/images/5.PNG)

It will also pop up the printing menu, which we will discuss in the **Printing** section.

## Manual Setup

### Moving and Rotation

To move the print around the print bed, first click the item you wish to move, and you will see two arrows pop up around your shape, as well as 3 quarter rings.

![image](/images/6.PNG)

Once that happens you can either move it on the main axis by dragging those arrows, or just grab and drag the object to wherever you want it.

You can also rotate it by grabbing and dragging the quarter rings or the (![icon](/images/7.PNG)) icon.



It is recommended to rotate the object so that the least amount of overhang is achieved:

![image](/images/8.png)

And there are no shapes that create cups:

![image](/images/9.png)

Again a menu with certain options will also appear next to the (![icon](/images/10.PNG)) icon.

![image](/images/11.PNG)

The `Auto-Orient Selected` will rotate the object to have the optimal setup.

![image](/images/12.PNG)

The {{% badge %}}Orient To Face{{% /badge %}} button will allow you to click on a face of the print and the program will lay it flat against the print bed such that the arrow that appears will point straight down into the bed.

![image](/images/13.png)

You can also edit its rotation more precisely by clicking the arrows next to `Orient X`, `Orient Y`, and `Orient Z` to rotate it around those axes.

![image](/images/14.PNG)

There also is a handful of options labeled `Orient To Bounding Box`. This will lay the face of the rectangular box around the object flat against the bed.

![image](/images/15.PNG)

Finally the {{% badge %}}Reset Selected{{% /badge %}} button will return the object to it's original orientation.

### Scaling

To scale your object, select the object, then select the (![icon](/images/16.PNG)) icon. A menu will appear next to the icon.

![image](/images/17.PNG)

The text boxes allow you to set the scale of the object by a multiple of it's current size and scale it evenly across all axis, or scale the axis separately to the size you specify.

The {{% badge %}}Reset{{% /badge %}} button will set the object to its original dimensions.

Alternatively, when you select the object you can grab and drag the (![icon](/images/18.PNG)) icon to scale it evenly.

### Layout

To manage the layout of the bed, select your object and hit the (![icon](/images/19.PNG)) icon. A menu will then appear.

![image](/images/20.PNG)

#### Auto Layout

To automatically layout your objects, you can change the `Model Spacing` and choose whether to select `Overlap Rafts` and `Lock Rotation`. Then hit the {{% badge %}}Layout All{{% /badge %}} button.

`Model Spacing` Will dictate how close the pieces end up after placement.

![image](/images/21.png)

`Overlap Rafts` dictates if the support rafts can overlap.

![image](/images/22.png)

`Lock Rotation` stops the program from rotating the models while arranging them.

#### Duplication

To duplicate your model, first select how many copies you want, then hit the {{% badge %}}Create{{% /badge %}} button.

#### Array
 
Array will duplicate your models in a regular pattern, with a specified number of rows and columns and specified spacing.

#### Mirroring

Hit the {{% badge %}}Mirror Models{{% /badge %}} button to mirror all selected models.

### Supports

To generate supports for your model, hit the (![icon](/images/23.PNG)) icon and a menu will appear. If you select an object or objects, you can generate supports only for the selected objects, or alternatively generate supports for all objects by not selecting any one particular object. 

![image](/images/24.PNG)

Firstly, you can automatically generate the supports by hitting the {{% badge %}}Auto-Generate All{{% /badge %}} button.

![image](/images/25.PNG)

You can paint on supports by hitting the {{% badge %}}Edit{{% /badge %}} button, but the details of that will not be covered here. It is recommended to use the Auto-Generate option instead.

You can edit the way supports generate in the **Basic Settings** section.

`Raft Type` will change how the support raft generates, either Full Rafts, Mini Rafts, or None.

![image](/images/26.png)

`Raft Label` will place the name of the object on the rim of the raft.

![image](/images/27.PNG)

`Density` Changes how often the supports will be placed.

`Touchpoint Size` changes the area of the contact between the support and the object.

`Internal Supports` will generate supports between different layers of the object.

**Advanced Settings** has more particular details but will not be covered on this guide.

Hitting the {{% badge %}}Reset{{% /badge %}} button will reset the objects completely.

Once you are happy with the object and support placement, move to the `Printer Settings` section.










