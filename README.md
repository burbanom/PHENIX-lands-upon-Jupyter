# phenix-visits-jupyter
A sample jupyter notebook along with ancillary files.  
Several parts of this jupyter demo borrow from the excellent lectures on scientific python found at https://github.com/jrjohansson/scientific-python-lectures. The instructions below can be found in more detail in Lecture 0.  

# Installation
## Conda
The best way set-up an scientific Python environment is to use the cross-platform package manager `conda` from Continuum Analytics. First download and install miniconda http://conda.pydata.org/miniconda.html or Anaconda (see below). Next, to install the required libraries for these notebooks, simply run:

    $ conda install ipython ipython-notebook spyder numpy scipy sympy matplotlib cython

This should be sufficient to get a working environment on any platform supported by `conda`.

### Linux
In Ubuntu Linux, to installing python and all the requirements run:

    $ sudo apt-get install python ipython ipython-notebook
    $ sudo apt-get install python-numpy python-scipy python-matplotlib python-sympy

