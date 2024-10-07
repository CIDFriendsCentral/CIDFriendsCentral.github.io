+++
alwaysopen = false
title = 'Smooth and Rough Carves'
date = 2024-05-08T09:32:56-04:00
draft = false
weight=2
+++
---
Once you have your file set up correctly, select both of your pieces and the rectangle around them and select the rough machining toolpath.

![image](/images/253.jpg)

Select your bit and make sure that `Machining Limit Boundary is set to "Selected Vectors." Then Hit calculate. Your toolpath should look like a rough outline of your shape

![image](/images/254.jpg)

Now go back, select both pieces and the rectangle, and select `Finish Machining Toolpath`.

![image](/images/255.jpg)

Now for the bit selection, hit `Select` and then look for a bit that is the same size as the one you used for the first path, but says `(Smooth Carve)` on the end. If this bit exists, simply select it and use it. If not, create a new bit with the same settings as your original bit, but with a `Stepover` of 10% or less, a spindle speed of 12000 RPM, and a feed rate and plunge rate of 6. Rename it the name of your bit followed by "(Smooth Carve)". Then select that bit you just made.

![image](/images/256.jpg)

 Make sure that `Machining Limit Boundary is set to "Selected Vectors" and calculate your path.

 ![image](/images/257.jpg)

You now have your cut file, and you are free to cut like any other piece. Go to the [Securing Material](https://cid.friendscentral.org/cnc/securing/index.html) section. 