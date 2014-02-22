Namecoin Graphics
=================

This is a repo for visual collateral (logos, badges, etc) for Namecoin.  Branding guidelines and other extensions are to come.  Feel free to experiment and expand on the designs.  Shading would be a good place to start.


Directory and Graphics Structure
================================
The "master" format for the graphics is in Illustrator.  The nmc-logo and nmc-triangle files are linked in the other graphics so that changes propogate.  I will eventually redo this using SVG but for now I have included straight SVG conversions.

Even with the export, however, the logo and triangle are both made of up cloned objects. This is great if you are going for precision but it's a PITA if you want to just shit done.  I've exported "flattened" versions in SVG format called "plain-n" and "plain-trangle" which are simple paths and shapes without any linking or cloning.

Exporting is semi-automated and will eventually be done using GULP or a similar build tool.  For now, I've included actions to convert to PNGs in /meta/ - they bring up the save-to-web screen with the correct settings. : /  JPEGs are created by converting PNGs.

| ![Logo](https://raw.github.com/indolering/nmc-graphics/master/png/250/nmc-coinage-front.png) |      ![Logo](https://raw.github.com/indolering/nmc-graphics/master/png/250/nmc-coinage-back.png) |
| :-----------: | -----------: |
