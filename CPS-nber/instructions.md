# Instructions for Current Population Survey
This provides instructions for downloading, cleaning and preparing CPS data, as available from the NBER.


## March 2017 CPS supplement
 - Download and extract the March 2017 CPS ASEC dataset here: http://www.nber.org/cps/cpsmar2017.zip
 - Save as a .dct file the March 2017 CPS data dictionary here: http://www.nber.org/data/progs/cps/cpsmar2017.dct
 - Read the CPS data into Stata using the following command: infile using "cpsmar2017.dct", using("asec2017_pubuse.dat")
 - Once it has been converted, save the CPS dataset in this repository as cpsmar2017.dta.

