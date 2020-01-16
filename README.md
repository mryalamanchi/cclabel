# cclabel

Python implementation of connected componenet labeling for binary images.

Algorithm is based heavily on [Optimizing Two-Pass Connected-Component Labeling by Kesheng Wu, Ekow Otoo, and Kenji Suzuki](http://dl.acm.org/citation.cfm?id=1529869&preflayout=flat)

Any errors in the implementation are soley my fault.

To see it in action, just run ./cclabel example.png

Further details are in the source


## INSTRUCTIONS:

  1) Check the version of `python` installed in your system using `python --version`, if none is installed then install python 3.7
  2) Similarly check the version of `pip` using `pip --version` and the python version it is attached to.
  3) Install `PIL` module using `pip install --user PIL` or `pip3 install --user PIL`
  4) If you are using python3 then open `cclabel.py` in a text editor and change the line `#!/usr/bin/python` to `#!/usr/bin/python3`
  5) Now place the image to perform operations on in the current directory along with `cclabel.py`
  6) Now you can run the program in 2 ways:
    *  ./cclabel.py 'name_of_the_image.filetype'
    * `python3 cclabel.py 'name_of_the_image.filetype'` or `python cclabel.py 'name_of_the_image.filetype'` depending upon the python version
