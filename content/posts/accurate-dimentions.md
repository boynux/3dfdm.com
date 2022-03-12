---
title: Accurate Dimensions
date: 2022-03-12T00:00:00Z
featured_image: 'images/xyz-cube.jpg'
images:
  - images/xyz-cube.jpg
draft: false
---

Oftentimes printing with accurate dimensions down to 10th of millimeter is not a big issue. For instance if you are printing a single piece object like a statue it doesn’t really matter if that’s 0.1 millimeter larger or smaller in Y axis or X axis or both.

But sometimes the pieces that you are printing need to fit perfectly into each other or maybe need to be compatible with some non 3d-printed parts, like a 3d printed RC car that "I buit recently (maybe another article on that later).  In these cases it’s very important that the print dimensions are as accurate as possible.

There are a few factors you need to consider to get the end result down to 0.1 of millimeters accurate.

## Printers step motor settings

This is probably the most important factor, although most printer settings are adjusted at the factory with the right settings, in my experience sometimes they need some more calibrations. In order to adjust the printer’s step motor settings follow the following steps:

1. Print an object that’s simple and has a known width, length and height. I typically use [XYZ calibration cube](https://www.thingiverse.com/thing:1278865) for that matter.It’s simple and fast to print. It’s very important to make sure you use the standard filament temperature and flow rate also set to the normal value that you typically use.
1. It’s 20x20x20 mm in dimensions, but technically you can choose any other object.
Using a caliper measure the dimensions of the printed object, if there are any mismatches in any of x,y or z dimensions you will need to adjust the settings for that axis respectively. 
Let’s say you measure the width (y) of the cube 20.4 mm (O) that means your printer is printer larger that expected., check the current steps per mm settings for the printer (S), let’s say it’s set to 400 as for instance.. 

The new steps per mm setting is calculated via this formula: 
`(E/O) * S = your new number of steps per mm`

In this example that would be: `(20.00 / 20.40) * 400 = 392`

In this case, we need to adjust the step per mm settings for the x axis to 392.

1. Print the same object again and measure the dimensions, as a rule of thumb if the measurement deviation is less than 0.2 mm you are good. 

## Printing temperature

The printing temperature is another factor in variations in the dimension, typically if at higher temperatures the objects tend to get a little larger due to over extrusion. If you need to print at very high temperatures, for example to have a better bonding between the layers, make sure to compensate for the additional flow rate by slightly reducing the extrusion multiplier.

For this case a simple object with known dimension can be a good test print to adjust the temperature or extrusion to the right numbers.

## Over extrusion

Like high temperature, over extrusion can cause the printed object to be slightly larger than the original one, specially around the holes. Again print a test object a couple of times and adjust the extrusion multiplier until to get close to 0.1 mm accuracy.

## Adjust your print size

If none of the above helped to get more accurate results, as the last resort you can alway scale the original object to slightly smaller or larger to get the exact dimension that you are after.

Thank you for reading up to here. Let me know if there are other parameters that can affect the print dimensions.

