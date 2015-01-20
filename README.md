jov-white-matter-matters
========================

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/arokem/jov-white-matter-matters?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Examples of diffusion MRI analysis for vision science. Supplementary material to: 

"The visual white matter matters! Application of diffusion MRI and fiber tractography to vision science" 

Rokem, A. Takemura, H., Bock, A. Scherf, S., Bridge, H., Fine, I., Behrmann, M., Wandell, B., Van Essen, D., and Pestilli. F.

To see the rendered notebooks go to: XXX Link to nbviewer.

## Instructions

To run these notebooks, you will need to install the
[`IPython`](http://ipython.org) software, as well as [`dipy`](http://dipy.org).

One way to install these is by using the (free) Anaconda software distribution:

- Go to the [Anaconda website](http://continuum.io/downloads) and follow the
  instructions therein to download and install the distribution for your
  platform.

- To install `dipy` and all the other dependencies, type:

        conda install scikit-learn vtk ipython pip
        pip install dipy 

   At a terminal/shell window. This should download and install all of the
   required software dependencies to run all of the 
   
Once you have followed these instructions, you should have all the software
needed installed on your computer. To start running the notebooks, change the
working directory of your terminal to the directory where you have downloaded
the notebook files (using `cd`) and type:

    ipython notebook

A browser window should open with a list of notebook files. Start by reading
the `index` notebook and follow the instructions from there.




