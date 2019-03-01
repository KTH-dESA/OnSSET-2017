# OnSSET-2017
The 2017 version of the Open Source Spatial Electrification Tool (OnSSET), developed by KTH-dESA (www.desa.kth.se). The tool is used to calculate least-cost investment scenarios for universal electrification, drawing on geo-spatial data.

### Content

This repository contains the 2017 version of the OnSSET tool, implemented in Python. To tun the tool four files are needed; two Python files and two input files.
1) **onsset.py**. This file contains all the methods used to perform the calculations of the OnSSET tool.
2) **runner.py**. This file is used to read the input files, and use the methods defined in onsset.py to calculate the least-cost investment scenarios.
3) **Specs.xlsx**. This input file contains key data relating to the country or region to be studied.
4) **Togo.csv**. This input file contains the GIS data extracted to .csv format required to run the analysis, for Togo.

Further, a document called "How to Run Instructions" is available.

### Branches

This repository contains two branches, **master** and **Updated version 2018**.
* The **master** branch contains the 2017 version of the OnSSET code
* The **Updated version 2018** branch has a slightly modified version of the code from June 2018. The functionality of the updated code is the same as in the master branch (they give the same results within ~1%), but with faster running times and a modified method of selecting input files.

### How-to-use Instructions

To be able to run the code you need to have Python 3 installed, along with a number of packages. The easiest way to get the packages needed may be to download Anaconda. Follow the below steps to use the tool:

1. Clone repository in a directory of your preference
2. Open onsset.py and runner.py in the IDE of your preference (Pycharm is suggested)
3. Install dependencies
4. Make sure that specs.csv and Country.csv (e.g. Togo.csv) files are in the same directory. Both files shall follow the format and naming convention as shown in the sample files in this repository. Parameter values can be changed accordingly
5. Run onsset.py and make sure there is no error
6. Run runner.py a. Select to calibrate the Country.csv as per instructions b. After calibration (taking place only once) start running scenarios as per instructions.
7. After a scenario is run two output files will appear in the directory; one containing full results and another providing a summary.
8. Import the full result scv file into a GIS environment (QGIS, ArcMap) to vizualize the results.

### Supplementary material

Find more information about the OnSSET tool at www.onsset.org and the user manual at https://onsset-manual.readthedocs.io/en/latest/.

To create the input .csv file for another country, information and code can be found here: https://github.com/KTH-dESA/GIS-extraction_for_OnSSET

For any additional information please contact the KTH team here: http://www.onsset.org/contact--forum.html
