# Overview

3d CAD model for a battery height spacer to allow installing a shorter group 94R battery in place of a taller 24F or 27F one.

## Pros

- 94R is widely available as an AGM battery *and much more affordable* compared to 27F.
- In terms of capacity, it is a significant upgrade over 24F and comes close to 27F. 
  It usually provides the lowest cost per capacity.
- It has the same size footprint as 27F and therefore fits in the battery compartment of the 4th-gen Toyota 4Runner (N210/N215).

## Cons

- It has quite a bit less height (see below for details).
  This requires bending back the tiny 90° tab on the body ground connector to allow rotating it downwards and securing the clamp to the terminal.
- It has a narrower top with a gap for the folding handles.
  This is somewhat incompatible with the narrow factory steel hold-down bar.

This spacer provides a longer, sufficiently wide bed for a flat hold-down bar intended for a 24F or 27F battery.
The goal is to reduce movement and strain on the battery case.

# Status

- 3d model complete.
- Prototype printed using ABS filament with scale factor on printer set to 108% and installed (see [photo](./photo.jpg)).

# Battery sizes

## Capacity and Length/width/height:

- Group 24F (65Ah):          282     168     229
- Group 27F (92Ah):          318     173     227
- Group 94R (H7/L4) (80Ah):  315     175     190

## Additional group 94R dimensions

- 121 mm battery width upper
- 12 mm wide and 5 mm deep gap for folding handles across width of battery 
- 25 mm step height between outer and inner top of battery 

## Dimensions of hold-down bar

- 45 mm width
- 8 mm height center
- 12 mm height ends
- 175 mm inside length; spacer needs to fit in there lengthwise


# Rough sketch

```
   175
*****************
*****************
*  121          *

*  45  *
********
   **
```

# Tools used

- [ImplicitCAD](http://www.implicitcad.org/) for programmatic CAD modeling
- [MeshLab](http://www.meshlab.net/) for 3d mesh rendering
- [Cura LulzBot Edition](https://www.lulzbot.com/cura) for printing

# References

- [Deka Intimidator AGM Automotive Flyer](https://www.eastpennmanufacturing.com/wp-content/uploads/Intimidator-Automotive-Flyer-1737.pdf)
