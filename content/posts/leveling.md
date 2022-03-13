---
title: "Leveling Your Printer"
date: 2022-03-10T20:57:36Z
featured_image: 'images/3dbenchy.jpg'
images:
  - images/3dbenchy.jpg
tags: [3dprint, leveling, print bed, first layer]
draft: false
---

Leveling the 3d printer is the first step to have good print results. But what leveling actually means and how do you know if your printer is leveled or not?

## What does leveling mean?

Leveling in 3d printers means:

- The hot nozzle distance to the bed is properly adjusted.
- This distance is consistent as the hot end moves over the entire surface of the bed.

## How do I know if the bed is leveled?

Look for one or more of the following signs:

- Hot end is scratching the bed surface.
- The first layer looks rough in some areas.
- Some lines in the first layer are not printed properly.
- Filament is not coming out of the hot end consistently.
- The first layer is not sticking to the surface.
- The print gets warped specially at the sharp corners.

Of course some of these signs could have other reasons, but I always suggest to make sure the printer bed is leveled before checking the other settings.

## How to level?

Leveling methods vary from one printer to the other, for detailed instructions I recommend consulting your printer's user manual or website. Here I’m going to described how you generally approach bed leveling:

1. Make sure the printer settings are all set to the default
1. Adjust z-index to 0.1 mm 
1. We are going to use 80 gram A4 paper (with 100 mic thickness) to level the bed, if you are using feeler gauge or other type of paper set the z-index accordingly.
1. Set the printer's hot end to home (using the printer’s controller).
1. Release the stepper motors.
1. Now move the hot end to the bottom-left corner of the bed. While make sure the vertical axis remains unchanged.
1. Slide the paper between the hot and and the bed
1. Tighten or loosen the adjusting screw for that corner until you feel the hot end just touches the paper (You can move the paper slightly to feel that better).
1. Repeat the same process for the other corners:
    - Bottom-right 
    - Top-right
    - Top-left 
1. Reset the z-index to zero
1. Done

## Easier approach

If you want to forget about bed leveling and focus on improving other settings of your 3d printer, I recommend adding an auto-leveling sensor to your printer. By doing that you are basically removing one (rather important) variable from the printer settings and you can use other parameters to achieve a perfect print.

I’m using [CR-Touch](https://www.creality3dshop.eu/products/creality3d-cr-touch-auto-bed-leveling-sensor-for-ender-series-3d-printer-with-4-2-2-4-2-7-motherboard?gclid=CjwKCAiA4KaRBhBdEiwAZi1zzjHamio9WtW8aRnOIx904bfD3KymJiix-fLnoGape-FGYT-rqjjBvBoCOAsQAvD_BwE) for my Ender 3 Pro printer and very happy about it so far. But you can also use other options like [BL Touch](https://www.creality3dofficial.com/collections/bl-touch?sca_ref=10788.CFDqhuwn3C).

