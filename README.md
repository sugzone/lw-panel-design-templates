# lw-panel-design-templates
[Loudest Warning](http://www.loudestwarning.co.uk/) format layout and design templates

This repo contains both [Affinity](https://www.affinity.studio/) files and PDFs for a variety of Loudest Format panel sizes: 1" NPW (nominal panel width), 2" NPW, 3" NPW, and 4" NPW.

Each size contains 6-row and 8-row layouts as well as split layouts in case you want to place parts diagonally.

There are also files with assets for commonly used panel-mount objects, sized for their mounting holes.

### Loudest Warning format

Resources used for specs: [this](http://www.loudestwarning.co.uk/portfolio/4u-modular-specs/) and [this](https://loudestwarning.tumblr.com/LW%20FORMAT).

When you put panel components on the first or last horizontal line of the guide/grid, they'll be centered at 7/8" from the top and bottom edges of the front panel respectively. Really that's 7/8" minus 1.4mm to conform with the LW spec of 175mm front panel height. That placement is compatible with 5.25" long PCBs.

### Note about these files

All files display 3.2mm round mounting holes at the top and bottom placed 3mm from the edge and at `NPW - 1"` per the LW spec.

Files in `/affinity/margin+guide templates` have only margins and column/row guides, and therefore are at full NPW to maintain the correct the column spacing. 

The files in `/affinity/vector grids (doepfer tolerance)` on the other hand are set up to be just a tiny bit narrower to match Doepfer tolerance specified in one of the links above. Those files have selectable layers for different row configrations.

The PDFs in `/PDF vector grids (doepfer tolerance)` can imported into your design software of choice. 

At some point I'd love to make some FPD templates for FrontDesign. We'll see if I do!

