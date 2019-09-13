# qc_pymol
Scripts for using pymol together with quantum chemistry programs. So far this includes utilities for plotting densities and electrostatic potentials.

Author: Felix Plasser

Note: these tools are still at a very rudimentary stage.

If you have any additions or improvements, please send me a pull request.

## Plotting of densities and electrostatic potentials

Load the script file from the PyMOL console
~~~~
run <qc_pymol>/dens_plot.py
~~~~

Plot a density given as cube file
~~~~
show_dens dens.cube
~~~~

Map the ESP onto the density
~~~~
map_esp dens.cube, esp.cube
~~~~

Information about all the contained functions and options
~~~~
dens_plot_help
~~~~
