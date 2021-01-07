![Logo here](.img/RestraintMaker_logo_withBackground.png)

# Welcome RestraintMaker

## Introduction

## Examples

## Content

### Using

### Development
Restraint make is split two parts.
* RestraintMaker
  This part is the core of the program. It can be executed as standalone.
    * algorithm
    * tools_Rdkit
    * io
    * utils
    
* Interface Pymol
    
## Installation
You can retrieve the repository from GitHub:
https://github.com/rinikerlab/restraintmaker

### Using
  * Install via Pymol Plugin Manager
    WIP
  * Install via Anaconda
    WIP

### Development
  For development purposes: 
   * Install with Anaconda
   
    #!/usr/bash
    # 1. Retrieve the repository
    git clone url restraintmaker
    cd restraintmaker
        
    # 2. generate an Anaconda environment with the enviornment file:       
    conda create -n restraintmaker --file devtools/conda-envs/environment_unix.yaml
        
    # 3. Test    
    python examples/example_gui.py
       

## Author
Benjamin Ries,
Clemens Rhiner
    
## Acknowledgments
