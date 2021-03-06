                  +----------------------+
                  |   artoolkit_utils    |
                  +----------------------+

[![Build Status](https://travis-ci.org/arnaud-ramey/artoolkit_utils.svg)](https://travis-ci.org/arnaud-ramey/artoolkit_utils)

ARToolKit ( http://www.hitl.washington.edu/artoolkit/ ) is a computer tracking
library for creation of augmented reality applications that overlay virtual
imagery on the real world.

It works with so-called pattern files, representing the visual appearance of
the markers. These patterns are then searched in the input stream of image.

Two programs are given here:
* One can transform color or BW images into ARToolkit patterns.
* One can transform ARToolKit patterns into images for visualizing them

It requires OpenCV and curl.

License :                  see the LICENSE file.
Authors :                  see the AUTHORS file.
How to build the program:  see the INSTALL file.

________________________________________________________________________________

How to use the program
________________________________________________________________________________
To display the help,
run the generated executables 'artoolkit_img2patt'
or 'artoolkit_patt2img' with no arguments.
It will display the help of the program.

