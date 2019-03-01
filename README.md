# OnSSET-2017
The 2017 version of the Open Source Spatial Electrification Tool (OnSSET), developed by KTH-dESA (www.desa.kth.se). The tool is used to calculate least-cost investment scenarios for universal electrification, drawing on geo-spatial data.

### Content

This repository contains the 2017 version of the OnSSET tool, implemented in Python. To tun the tool four files are needed; two Python files and two input files.
1) onsset.py. This file contains all the methods used to perform the calculations of the OnSSET tool.
2) runner.py. This file is used to read the input files, and use the methods defined in onsset.py to calculate the least-cost investment scenarios.
3) Specs.xlsx. This input file contains key data relating to the country or region to be studied.
4) Togo.csv. This input file contains the GIS data extracted to .csv format required to run the analysis, for Togo.

Further, a document called "How to Run Instructions" is available.

### How-to-use Instructions

To be able to run the code you need to have Python 3 installed, along with a number of packages. The easiest way to get the packages needed may be to download Anaconda. Follow the below steps to use the tool:

1. Clone the repository (or download the four files) to a folder on your computer.
2. Run the runner.py file.
3. Follow the instructions in the "How to Run Instructions" document.

### Supplementary material

Find more information about the OnSSET tool at www.onsset.org and the user manual at https://onsset-manual.readthedocs.io/en/latest/.

To create the input .csv file for another country, information and code can be found here: https://github.com/KTH-dESA/GIS-extraction_for_OnSSET
