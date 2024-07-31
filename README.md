# Understanding the impact of climate change on satellite communication

This repository contains codes necessary to download and process precipitation data from various sources to perform long-term rainfall statistic analysis in accordance with ITU 837.
ITU837 Annex 2 recommends using sub-hourly rainfall data to be input into their Matlab program to obtain R0.01% exceedance value at 1-min integration time. The codes in this repository will do exactly that and prepare the data for the Matlab program.

This repository contains the following folders
1) Data Acquisition - Download and obtain open-source climate data into grid or matrix form --> nc files
2) Data extraction - Extract point data from gridded files into CSV for comparison
3) Data manipulation - Compare performances of datasets and apply bias correction. A CDF will be generated which will then be input into the Matlab program

## End goal:
To develop a model that:
1) Is able to provide bias-corrected data for areas without rain gauges
2) Is able to obtain high-resolution data
3) Is able to provide accurate R0.01% data from historical rainfall records
4) Is able to take in climate model projections data and obtain future R0.01% estimation


Overview of rainfall attenuation model (Blue highlights scope of study):

![image](https://github.com/user-attachments/assets/78f81829-1837-4483-9f4f-3ea361a327fa)

Matlab output

![image](https://github.com/user-attachments/assets/127075d6-899b-4431-ae12-f7440a44e4c2)


## Getting started

Cloning files from github

Open command line interface and type: ```git clone https://github.com/awpbash/rainfall_analytics.git```

Installing depadancies

```pip install -r requirements.txt```



## Future work

More datasets could be explored and assessed on their suitability for use. Furthermore, other downscaling methods could also be explored as downscaling inherently introduces uncertainty in the data. Last but not least, the scope of the study could be extended to include other variables recommended by ITU 618 to comprehensively evaluate the impact of climate change on SATCOM communication.


References:
1) https://www.itu.int/rec/R-REC-P.837/en
2) https://www.itu.int/rec/R-REC-P.618/en
3) https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=224718
