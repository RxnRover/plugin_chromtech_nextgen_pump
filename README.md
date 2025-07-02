# ChromTech Next Generation Plugin

This plugin provides basic control over ChromTech Next Generation pumps, 
including flow rate control, start and stop commands, and pressure monitoring.
The plugin keeps a log of all data collected in a CSV format for easy analysis
using a spreadsheet program.

## Installation

ChromTech Next Generation pump drivers are required to communicate with the 
pumps. Download the drivers from 
[here](https://www.github.com/RxnRover/driver_chromtech_next_gen) and extract
the files into your `<labview>/instr.lib` directory, where `<labview>` is the
location of your LabVIEW installation.

For install using VIPM download the latest `.vip` from the [Releases tab](https://github.com/RxnRover/plugin_chromtech_nextgen_pump/releases)

Download this plugin by clicking the "Code" button in the top right of its 
GitHub repository and selecting "Download ZIP". Extract the ZIP file into your 
`<documents>/Plugins/Hardware/Pumps/` directory to finish installation. 
Create the `ReactorComponents` subdirectory if it does not already exist.
