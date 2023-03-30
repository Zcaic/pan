# pyPanair
A pre/post processor for Panair.  
"Panair" and "Panin" are not included in this repository.  
A copy of these software can be obtained at [Public Domain Aeronautical Software](http://www.pdas.com/contents15.html).  

## What can "pyPanair" do?  
List of things that pyPanair can do (check the examples)
* Define the geometry of a wing in the LaWGS format (tutorial 1 & 2)
* Define the geometry of a wing/body configuration in the LaWGS format (tutorial 3)
* Convert LaWGS format files to stl format (convert_wgs)  
* Convert agps format files to vtk (legacy Paraview), vtm (multiblock Paraview),
 or dat (multiblock Tecplot) format (convert agps)  
* Calculate the local lift / pitching moment coefficients from agps files (section_force_calculation)
* Parse ffmf files (convert_ffmf)  

## Installation
Download the repository and type

```commandline
python setup.py install
```

or if you have git installed, simply type

```commandline
pip install git+https://github.com/SaTa999/pyPanair
```

## Requirements
pyPanair requires python 3.5+  
(tests have only been performed for python 3.6)  
An [Anaconda3](https://www.continuum.io/) environment is recommended.

## Example
Example scripts and files are bundled in the "examples" directory.  

## Tutorial
Tutorials of `pyPanair` are included in `examples` directory.