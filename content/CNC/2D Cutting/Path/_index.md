+++
alwaysopen = false
title = 'Path Settings'
date = 2024-05-08T09:32:56-04:00
draft = false
+++
---

Once you have your vector file, we will create cut paths for the file

Once you have the vectors, you need to turn them into toolpaths in order for the shopbot to be able to cut them.

Open the toolpaths tab on the top right corner of Aspire. It will create a menu on the right side. 

Image

Pin this menu by clicking the pin button in the top right corner of the menu that opens up so it's easier to access.

Image 

To create a toolpath: first, select the vector that you would like to turn into a toolpath. Then, press one of the buttons in "Toolpath Operations" that look like wood (in the top three rows). This will make a toolpath out of the selected vector. There are some settings that you will have to adjust in the menu that appears. 

Image

When the settings are correct, scroll down to the bottom of the tab with the scrollbar on the right and click the {{% badge %}}Calculate{{% /badge %}} button to finish making the toolpath. This will display a preview of your cuts. Hit *Clear Preview* and then *Preview all Paths* to see what the paths will carve

Image

Repeat this step with each vector part to create all of the toolpaths. 

If you want to edit a toolpath, press the {{% badge %}}Edit Toolpaths{{% /badge %}} button. To delete a toolpath, right click it in the toolpaths section below and press delete > this.

When you are done with creating and editing the toolpaths, export them by pressing the {{% badge %}}Save Toolpaths{{% /badge %}} button. Make sure the toolpaths you want to export have the checkmark next to them checked.

Image

In the menu that appears after clicking the {{% badge %}}Save Toolpaths{{% /badge %}} button, make sure these settings are selected:

- Visible toolpaths to one file
- Machine: CID Shopbot
- Post Processor: ShopBot TC (inch)(*.sbp)

Then press the {{% badge %}}Save Toolpath(s) ...{{% /badge %}} button at the bottom.

This will export your toolpaths as a .sbp file.

Once you have done this, move to the cutting page.


