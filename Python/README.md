## Pygmo

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
    
