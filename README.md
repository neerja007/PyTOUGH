# What is PyTOUGH?

PyTOUGH (Python TOUGH) is a Python library for simplifying, extending and automating the use of the [TOUGH2](http://esd.lbl.gov/research/projects/tough/) subsurface fluid and heat flow simulator. Using PyTOUGH, it is possible to automate the creation and editing of TOUGH2 model grids and data files, and the analysis and display of model simulation results, using Python scripts.

# Installing PyTOUGH:

First, make sure you have [Python](http://www.python.org) (note: use Python 2.x- Python 3.x is not supported at present) and the [Numerical Python](http://numpy.scipy.org/) library installed on your machine.  (For some features you will need other libraries such as [Scientific Python](http://www.scipy.org/) or [Matplotlib](http://matplotlib.sourceforge.net/)- consult the user guide for details.)

Click the [Download ZIP](https://github.com/acroucher/PyTOUGH/archive/master.zip) button at the right of the PyTOUGH web page, and save the .zip file to your computer.  Unzip this to any directory on your computer.  This will create a directory containing a file called `setup.py`.  At the command line type `python setup.py install`.

# More information:

For more detailed information on PyTOUGH, consult the user guide (PDF format, in the 'doc' directory of your PyTOUGH install) and the PyTOUGH [wiki](https://github.com/acroucher/PyTOUGH/wiki/), which has links to published articles on PyTOUGH.

# What's new in PyTOUGH?

The latest stable version is 1.3.9, which has:

* Improved user guide: added index, added hyperlinks from tables to descriptions of properties/methods, fixed bug which prevented searching PDF for strings containing underscores, added hyperlinks to external URLs, improved formatting of code examples (with syntax highlighting)

* Better support for exporting grids containing columns with more than four sides to VTK

* Ability to plot connection flow arrows on mulgrid layer and slice plots

* Improved calculation of column centroids

* Improved calculation of connection geometry parameters and flux matrices

* new demote_block() method for t2grids- to move blocks to the end of the block list

* improved reading of some AUTOUGH2 listing files

* improved reading of some exotically-formatted Fortran floating point data

as well as various bug fixes and other minor enhancements.

# Where's the user guide?

Since PyTOUGH version 1.3.6, the PyTOUGH user guide (PyTOUGH-guide.pdf) is now included in the 'doc' directory of your PyTOUGH install.  Previously this was available separately from the 'Downloads' section on the website, but GitHub decided to phase out this 'Downloads' section.

