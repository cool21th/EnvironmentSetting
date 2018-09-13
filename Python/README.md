## [Pygmo](http://esa.github.io/pygmo/index.html)

PyGMO (the Python Parallel Global Multiobjective Optimizer) is a scientific library providing a large number of optimisation problems and algorithms under the same powerful parallelization abstraction built around the generalized island-model paradigm. 


Conda is a good default choice in Linux and OSX.
The pip packages are also available on Linux for those users who might prefer pip to conda, but they are not available on OSX.

Conda

    conda config --add channels conda-forge
    conda install pygmo
    
Pip

    pip install pygmo


Download install 
  
    git clone https://github.com/esa/pagmo.git
    cd pagmo
    mkdir build
    cd build
    ccmake ../
    
