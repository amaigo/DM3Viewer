DM3Viewer
=========

DM3Viewer is a simple PyQt application to view and export DM3 files.

DM3 files are produced by Digital Micrograph, an image processing program produced commercially by [Gatan](http://www.gatan.com/).
I have tried to make the program as reliable as possible but I can not guarantee that the program works well with all (or any)
DM3 files because (i) I did it for my own personal use, not to be a "professional" package and (ii) the DM3 file format is not
published by Gatan. Said that, if you find that it fails with a given file you can send it to me and maybe I can make it work.

Version history
===============

- Version 0.1.0 (Feb 05, 2018).

Digital Micrograph file format
==============================

The file format for Digital Micrograph is not published by [Gatan](http://www.gatan.com/).

The script that parses .dm3 files in DM3Viewer is based on the script [Python DM3 Reader](http://imagejdocu.tudor.lu/doku.php?id=plugin:utilities:python_dm3_reader:start),
developed by [Pierre-Ivan Raynal](http://microscopies.med.univ-tours.fr/). DM3lib, in turn, is based on the [DM3_Reader plug-in](https://imagej.nih.gov/ij/plugins/DM3_Reader.html)
for [ImageJ](https://imagej.nih.gov/ij/) that was developed by Greg Jefferis. I have also taken a peak at the script  heavily used the excellent information available here:
 - [http://www.er-c.org/cbb/info/dmformat/](http://www.er-c.org/cbb/info/dmformat/)
 - [https://imagej.nih.gov/ij/plugins/DM3Format.gj.html](https://imagej.nih.gov/ij/plugins/DM3Format.gj.html)

Requirements
============

 - Python (>=2.7)
 - Numpy (>=1.0.3)
 - Scipy (>=0.5.2)
 - Qt (>=4.2.3)
 - PyQt (>=4.2.3)
 - Matplotlib (>=1.5.0)

Installation
============

Linux:
------
 - Select the appropiate file (.deb or .rpm) and install using the package manager of your distribution.

Windows:
--------
 - Run Install_DM3Viewer_0.1.0.exe.

All:
----
 - You can also use Python to execute the file DM3Viewer.py contained in sources. In that case, you need to satisfy all the requirements listed above.

License
-------

GPL v3+