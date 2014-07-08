Namecoin Graphics
=================

This is a repo for visual collateral (logos, badges, etc) for Namecoin.  

##Namecoin Blue
* **Hex** \#7CA3CC
* **Lab** L: 66 a: -3 b: -25  / 66, -3, -25
* **RGB** R: 124 G: 163 B: 204 / 124, 163, 204
* **HSB** H: 211 S: 39 B: 80 / 120, 39, 80 
* **CMYK** C: 39 M: 20 Y: 0 K: 20 / 39, 20, 0, 20 

You can find associated color pallettes [here](http://paletton.com/#uid=13A0u0kdAIF3ZYj8SRJhWytlSsx).

| ![Coin Front](https://raw.github.com/indolering/nmc-graphics/master/png/500/nmc-coinage-2up.png) | ![Badge](https://raw.github.com/indolering/nmc-graphics/master/png/250/badge-prototype.png) |      ![Mini-Logo](https://raw.github.com/indolering/nmc-graphics/master/png/100/nmc-logo-mini.png) |
| :-----------: | :-----------: | -----------: |
| Coin Mockup | Namecoin Nerd Merit Badge | Mini Logo |

![logo license](http://i.creativecommons.org/l/by-sa/4.0/80x15.png)


Directory and Graphics Structure
================================
The "master" format for the graphics is in Illustrator.  The nmc-logo and nmc-triangle files are linked in the other graphics so that changes propogate.  I will eventually redo this using SVG but for now I have included straight SVG conversions.

Even with the export, however, the logo and triangle are both made of up cloned objects. This is great if you are going for precision but it's a PITA if you want to just shit done.  I've exported "flattened" versions in SVG format called "plain-n" and "plain-trangle" which are simple paths and shapes without any linking or cloning.

Exporting is semi-automated and should eventually be done using GULP or a similar build tool.  For now, I've included Illustrator actions to convert to 1000px PNGs as well as XnConvert scripts for 100px, 250px, and 500px in /scripts/.

License
=======
Everything here is licensed under the [CC-BY-SA](http://creativecommons.org/licenses/by-sa/4.0/deed.en_US) license EXCEPT that you don't have to attribute anything.  No, really, we don't want you to have to plaster our names on your graphic as long as you are sharing the source files.  However, all this stuff IS trademarked so, uhh, don't go getting a tattoo if you are General Hayden. 
