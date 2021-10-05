How to Run
==========

Basic Mode
----------

$ ph-puml mycode/src > class.puml
$ ph-puml mycode/src class.puml

This outputs class.puml in the current directory, so you may want to specify a path.

Running with the Advanced Features
----------------------------------

ph-puml generates PlantUML puml file syntax by default, but you can also export most output formats supported by PlantUML directly.

Currently, these are:

* eps (Postscript)
* latex (LaTeX/Tikz)
* latex:nopreamble (LaTeX/Tikz without preamble)
* png (PNG image)
* svg (SVG vector image)
* scxml (SCXML state chart, seems broken in PlantUML Version 1.2020.26)
* txt (ASCII art)
* utxt (ASCII art with unicode letters)
* vdx (VDX image)
* xmi (XMI metadata description)

Example Usage
+++++++++++++ 

$ ~/n/ph-puml/bin/ph-puml /my/code/dir -p /usr/share/plantuml/plantuml.jar -f svg > ~/mycode.svg

