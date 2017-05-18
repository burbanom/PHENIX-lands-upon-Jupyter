# PHENIX-lands-upon-Jupyter
A collection of jupyter notebooks along with ancillary files.  
Several parts of this jupyter demo borrow from the excellent lectures on scientific python by [J.R. Johansson](https://github.com/jrjohansson/scientific-python-lectures). The instructions below can be found in more detail in Lecture 0 of that lecture series.  

# Installation
## Conda (Linux & MacOS & Windows)
The best way set-up an scientific Python environment is to use the cross-platform package manager `conda` from Continuum Analytics. First download and install the Python 3 version of [Anaconda](https://www.continuum.io/downloads). Next, to install the required libraries for these notebooks, simply run:

    $ conda install numpy scipy sympy matplotlib jupyter pandas cython ase pymatgen MDAnalysis

This should be sufficient to get a working environment on any platform supported by `conda`.

### Linux
In Ubuntu Linux, to install Python 3 and all the requirements for this tutorial run:

    $ sudo apt-get install python3-pip
    $ sudo -H pip3 install --upgrade scipy numpy sympy matplotlib pandas cython jupyter ase pymatgen MDAnalysis

Although we will be using Python 3 in this tutorial, a similar procedure can be followed for Python 2.

## pycp2k
For the section on interfacing python with existing simulation software, please install [pycp2k](https://github.com/SINGROUP/pycp2k). **N.B.** You will need to have a [cp2k](https://www.cp2k.org/download) executable installed on your machine.

# Following the tutorial
## Git
As a nice continuation with previous tutorials from the MdlS, you can follow this tutorial using Git. To do this simply run:
    
    $ git clone https://github.com/burbanom/PHENIX-lands-upon-Jupyter.git
    
or download the repository directly. 
