This repository contains codes necessary to download and process precipitation data from various sources in order to perform long-term rainfall statistic analysis in accordance with ITU 837.
ITU837 Annex 2 reccommends using sub hourly rainfall data to be input into their Matlab program to obtain R0.01% exceedance value at 1-min integration time. The codes in this repository will do exactly that and prepare the data for the Matlab program.

This repository contains the following folders
1) Data Aquisition - Download and obtain open source climate data into grid or matrix form --> nc files
2) Data extraction - Extract point data from nc files into CSV for comparison
3) Data manipulation - Compare performances of datasets and apply bias correction. A CDF will be generated which will then be input into the Matlab program


References:
1) https://www.itu.int/rec/R-REC-P.837/en
2) 
