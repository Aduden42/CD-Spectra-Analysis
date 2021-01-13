# versioned_dir
This is a program to process CD data. Each dataset should be saved using the following pattern:
(B/S)_Tc(temp in Celsius)_TPC(total protein concentration in uM)uM_AB(total amide bonds)_PL(path length of cell in mm)mm_Ti_(title).txt
If the sample is the blank it should start with B, if it is a sample it should start with S
The blank should not contain the TPC and AB variables.
All brackets should be replaced with the required value. For example:
S_Tc20_TPC10um_AB30_PL1mm_Ti_10uM Folded Protein Sample.txt
This would be a sample with:
•	Temperature of 20̊C
•	Total protein concentration of 10uM
•	Total amide bonds of 30
•	Cell path length of 1mm
•	Title of “10uM Folded Protein Sample”
All files for processing should be put in the same directory as the program. There should be only one blank. Run the script, scroll to the bottom and the graphs can be copied or saved.
