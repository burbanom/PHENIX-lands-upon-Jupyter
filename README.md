# jupyter-comes-to-PHENIX
A sample jupyter notebook along with ancillary files.  
Several parts of this jupyter demo borrow from the excellent lectures on scientific python found at https://github.com/jrjohansson/scientific-python-lectures. The instructions below can be found in more detail in Lecture 0 of that lecture series.  

# Installation
## Conda (Linux & MacOS & Windows)
The best way set-up an scientific Python environment is to use the cross-platform package manager `conda` from Continuum Analytics. First download and install the Python 3 version of Anaconda https://www.continuum.io/downloads. Next, to install the required libraries for these notebooks, simply run:

    $ conda install numpy scipy sympy matplotlib jupyter pandas cython ase pymatgen MDAnalysis

This should be sufficient to get a working environment on any platform supported by `conda`.

### Linux
In Ubuntu Linux, to install Python 3 and all the requirements for this tutorial run:

    $ sudo apt-get install python3-pip
    $ sudo -H pip3 install --upgrade scipy numpy sympy matplotlib pandas cython jupyter ase pymatgen MDAnalysis

Although we will be using Python 3 in this tutorial, a similar procedure can be followed for Python 2.

# Following the tutorial
## Git
As a nice continuation with previous tutorials from MdlS, you can follow this tutorial using Git. To do this simply run:
    
    $ git clone https://github.com/burbanom/jupyter-comes-to-phenix.git
    
or download the repository directly. 
