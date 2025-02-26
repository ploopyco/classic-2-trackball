# Appendix B: 3D printed parts

# Buying 3D-printed parts from us
Not everyone has access to a 3D-printer. [That's why we sell kits with everything you need to build a Ploopy Classic 2 Trackball](https://ploopy.co/product-category/classic-2/). Here's why that's great for you:

- You get all of the 3D-printed parts, guaranteed free of manufacturing defects
- You won't waste time spending hours tweaking settings
- We guarantee it will fit together *perfectly*

Consider it. You're a smartie. You'll get there.

# Printing your own parts

So, you have a printer and want to print your own parts? Great! We don't have specific instructions, since every printer setup is different. All of the STLs are available, and if you need to make tweaks, you can alter the design files.

Here are the settings we use when we print parts. **Note that these settings have only been tested on the Prusa i3 MK2.5S and MK3S.** If you have another printer, you may need to tweak these settings.

- PLA. The geometry of many of the parts is quite complex; trying to use other materials may not result in success.
- 0.30mm layer height. You can go finer than this if you want, but we haven't tested that. Going coarser is not going to work; first, it's going to feel rough on your hand, and second, it won't accurately capture the necessary detail.
- Add supports to all of the pieces, but from the build plate only. They don't need to be everywhere.
- We changed the support material overhang threshold to 35 degrees (with the intention of reducing the amount of support material; some slicer programs have inverted settings, i.e. 55 degrees instead of 35, so do what's necessary). Any more support material is wasteful.
- Orient the pieces so that flat sides are on the build plate.
- We like gyroid for infill pattern, but anything is probably good. Cubic, rectilinear, whatever.
- We use 0.4mm nozzles. We haven't tested other nozzle sizes.