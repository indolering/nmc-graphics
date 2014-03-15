Namecoin Graphics
=================

This is a repo for visual collateral (logos, badges, etc) for Namecoin.  Most of it is still very raw and branding guidelines and other extensions are being worked on.  Feel free to flesh out the designs, even basic shading would be a good start.

If you are a professional design, we would like to go through a thorough design process and build a compelling visual identity for Namecoin.

| ![Coin Front](https://raw.github.com/indolering/nmc-graphics/master/png/250/nmc-coinage-front.png) |      ![Coin Back](https://raw.github.com/indolering/nmc-graphics/master/png/250/nmc-coinage-back.png) |
| :-----------: | :-----------: |
| Coin Mockup Front | Coin Mockup Back |

| ![Badge](https://raw.github.com/indolering/nmc-graphics/master/png/250/badge-prototype.png) |      ![Mini-Logo](https://raw.github.com/indolering/nmc-graphics/master/png/100/nmc-logo-mini.png) |
| :-----------: | -----------: |
| Namecoin Nerd Merit Badge | Mini Logo |


![logo license](http://i.creativecommons.org/l/by-sa/4.0/80x15.png)


Directory and Graphics Structure
================================
The "master" format for the graphics is in Illustrator.  The nmc-logo and nmc-triangle files are linked in the other graphics so that changes propogate.  I will eventually redo this using SVG but for now I have included straight SVG conversions.

Even with the export, however, the logo and triangle are both made of up cloned objects. This is great if you are going for precision but it's a PITA if you want to just shit done.  I've exported "flattened" versions in SVG format called "plain-n" and "plain-trangle" which are simple paths and shapes without any linking or cloning.

Exporting is semi-automated and should eventually be done using GULP or a similar build tool.  For now, I've included Illustrator actions to convert to 1000px PNGs as well as XnConvert scripts for 100px, 250px, and 500px in /scripts/.

License
=======
Everything here is licensed under the [CC-BY-SA](http://creativecommons.org/licenses/by-sa/4.0/deed.en_US) license EXCEPT that you don't have to attribute anything.  No, really, we don't want you to have to plaster our names on your graphic as long as you are sharing the source files.  However, all this stuff IS trademarked so, uhh, don't go getting a tattoo if you are General Hayden. 
