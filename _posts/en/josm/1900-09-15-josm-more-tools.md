---
layout: doc
title: More Tools
permalink: /en/josm/more-tools/
lang: en
category: josm
---

More Tools
============

The **buildings_tools** and **utilsplugin2** plugins add great additional
functionality into JOSM. In this section we'll take a closer look
at the functions they provide.

The Buildings Tools Plugin
--------------------------

-   If you haven't already, install this plugin following the instructions
    in [JOSM Plugins](/en/josm/josm-plugins).

![Buildings tools plugin][]

The Buildings Tools plugin is very helpful for digitizing buildings.
It allows you to trace one side of a rectangular building, and easily
extend the shape. If you are digitizing many buildings, this plugin
will save you clicks, and thereby save you time.

Once the plugin has been installed you will see a new button on the left
side of JOSM, which looks like this:

![Buildings tools button][]

-   Start JOSM and create a new empty layer.
-   Select the building tool and click twice to draw a line on the map.

![Draw edge][]

-   Then extend the mouse and click again to draw a rectangle.

![Extend building][]

-   This will not only create a rectangle with only three clicks, but
    it will also automatically apply the building=yes tag to the shape.

### Complex Buildings

You can also create more complicated buildings by first drawing several
overlapping buildings and then merging them together.

-   Draw two buildings which over lap, so that they form an L shape.
-   Select both buildings (hold SHIFT to select more than one object).
-   Go to Tools->Join overlapping Areas or press SHIFT+J on your keyboard.

![Merge buildings][]

### Edit Settings

Furthermore, you can alter the default settings of the plugin.

-   Go to Data->Set buildings size.

![Set buildings size][]

-   If you are creating many similarly sized buildings, you can set specific
    width and height dimensions of the buildings, such as 6 x 10 meters (the unit
    is in meters).

![Set buildings size dialog][]

-   By setting the dimensions you will only need two clicks to create precisely
    sized buildings.

Lastly, you can click on the Advanced button if you would like to add additional
tags that will automatically be applied to every building. For example,
if every building you draw is on the same street, you might add a tag
which identifies the street that will be automatically applied.

![Buildings advanced][]

Terracer
--------

-	To install this plugin, you can download and install Terracer by following 
the instructions from[JOSM Plugins](/en/josm/josm-plugins).

![Terracer plugin][]

The Terracer plugin is a simpler way of tracing and creating multiple quadrilaterals with same sizes.
For example, townhouses have the same length and width. Instead of tracing individual or copy-paste,
the mapper can create a single feature and divide it equally using the terracer. 

-	Once you have it installed, you can start by creating an outline or tracing the end of the whole area.

![Terracer trace buildings][]

-	After creating an outline, click the traced feature, go to More Tools and choose Terrace a building.

![Terracer More Tools option][]

-	The dialogue box will ask you to enter the housenumbers (for surveyors and townhouses) by
giving the lowest and highest number of the structure. You can also choose "All" or "Even/Odd" for 
the interpolation of the housenumbers. The housenumbers are just an option.
The amount of segments are also needed to identify how many features will be 
shown inside the outlined feature. 

![Terracer terrace a house][]

![Terracer dialogue box filled][]

-	After clicking the "Okay" button, the outlined feature will be divided into separate buildings
depending on the number of segments and housenumbers will be visible if there's any.

![Terracer outlined buildings][]

Good luck!


[Buildings tools plugin]: /images/en/editing/josm-more-tools/buildings_tools-plugin.png
[Buildings tools button]: /images/en/editing/josm-more-tools/buildings_tools-button.png
[Draw edge]: /images/en/editing/josm-more-tools/draw-edge.png
[Extend building]: /images/en/editing/josm-more-tools/extend-building.png
[Merge buildings]: /images/en/editing/josm-more-tools/merge-buildings.png
[Set buildings size]: /images/en/editing/josm-more-tools/set-buildings-size.png
[Set buildings size dialog]: /images/en/editing/josm-more-tools/set-buildings-size-dialog.png
[Buildings advanced]: /images/en/editing/josm-more-tools/buildings-advanced.png
[Terracer plugin]: /images/en/editing/josm-more-tools/terracer-plugin.PNG
[Terracer trace buildings]: /images/en/editing/josm-more-tools/terracer-trace-building.png
[Terracer More Tools option]: /images/en/editing/josm-more-tools/terracer-more-tools-option.png
[Terracer terrace a house]: /images/en/editing/josm-more-tools/terracer-terrace-a-house.png
[Terracer dialogue box filled]: /images/en/editing/josm-more-tools/terracer-terrace-a-house-filled.PNG
[Terracer outlined buildings]: /images/en/editing/josm-more-tools/terracer-outlined-buildings.PNG

