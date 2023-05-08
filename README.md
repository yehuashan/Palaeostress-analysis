There are three files in this repository: PALFD.for, C3.dat and RESULT.txt. 
PALFD.for is the code for our new method designed to estimate palaeostress from a low-diversity group of fault-slip data under the constraint of meaningful fault-slip pair(s). 
It is written in Fortran 90 and complied by Microsoft Developer Studio with Fortran PowerStation 4.0.  
Comments at the start of the code include:
1. Explanations of symbols of which the values are eithor read from a data file or, if needed, modified in main program. In the latter case, one may 
try to assign a slightly great value to CRANG3  if there is no meaningful fault-slip pair available in a data group under defaults.  
2. Output results of the RESULT.txt file.
An example and corresponding result, C3.dat and RESULT.txt , are included in the package. 
