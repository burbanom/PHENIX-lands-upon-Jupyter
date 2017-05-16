# PHENIX-visits-jupyter
A sample jupyter notebook along with ancillary files.  
Several parts of this jupyter demo borrow from the excellent lectures on scientific python found at https://github.com/jrjohansson/scientific-python-lectures. The instructions below can be found in more detail in Lecture 0.  

# Installation
## Conda (Linux & MacOS & Windows)
The best way set-up an scientific Python environment is to use the cross-platform package manager `conda` from Continuum Analytics. First download and install miniconda http://conda.pydata.org/miniconda.html or Anaconda (see below). Next, to install the required libraries for these notebooks, simply run:

    $ conda install numpy scipy sympy matplotlib jupyter cython ase pymatgen MDAnalysis

This should be sufficient to get a working environment on any platform supported by `conda`.

### Linux
In Ubuntu Linux, to installing python and all the requirements run (we'll be using python3 in this tutorial, but a similar procedure can be followed for python2):

    $ sudo apt-get install python3-pip
    $ sudo -H pip3 install --upgrade scipy numpy matplotlib cython jupyter ase pymatgen MDAnalysis

# Following the tutorial
## Git
As a nice follow-up with previous tutorials from MdlS, you can follow this tutorial using Git. To do this simply run:
    
    $ git clone https://github.com/burbanom/phenix-visits-jupyter.git
    
or download the repository directly. 
