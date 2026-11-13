# lw-panel-design-templates
[Loudest Warning](http://www.loudestwarning.co.uk/) format layout and design templates

This repo contains both [Affinity](https://www.affinity.studio/) files and PDFs for a variety of Loudest Warning format panel sizes: 1" NMW (nominal module width), 2" NMW, 3" NMW, and 4" NMW.

The folder for each width variant contains 6-row and 8-row layouts as well as split layouts in case you want to place parts diagonally.

There are also files with assets for commonly used panel-mount objects, sized for their mounting holes.

### Loudest Warning format specs

Resources used for specs: [Loudest Warning 4U specs page](http://www.loudestwarning.co.uk/portfolio/4u-modular-specs/) and [Loudest Warning tumblr post](https://loudestwarning.tumblr.com/LW%20FORMAT).

All files display 3.2mm round mounting holes at the top and bottom placed 3mm from the edge, spaced at `NMW - 1"` per the LW spec.

The top and bottom edges of these grids/guides sit 7/8" from the top and bottom edges of the front panel respectively. Really that's 7/8" minus 1.4mm to conform with the LW spec of 175mm front panel height. That placement is compatible with 5.25" long PCBs.

![diagram about NMW and panel height](http://www.loudestwarning.co.uk/wp-content/uploads/2015/02/LW-FORMAT-SPECS-V2-2000.png)



![diagram specifying row spacing and Doepfer tolerance](https://farm3.staticflickr.com/2896/13942823989_99f66fc943_b.jpg)

### Note about these files

Files in `/affinity/margin+guide templates` have only margins and column/row guides, and therefore are set at full NMW to maintain the correctly precise column spacing.

The files in `/affinity/vector grids (doepfer tolerance)` on the other hand are set up to be just a tiny bit narrower to match Doepfer tolerance specified in one of the links above. Those files have selectable layers for different row configrations.

The PDFs in `/PDF vector grids (doepfer tolerance)` can imported into your design software of choice. 

At some point I'd love to make some FPD templates for FrontDesign. We'll see if I do!

