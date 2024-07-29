Data manipulation

Data Comparison allows users to compare trends and patterns across various datasets. Just manually add the data variables at every step. 
*Important to adjust the units accordingly for high frequency analysis ie. Data.gov provides 5 minute data so x 12 to hourly rainfall

Bias_correction allows users to see and understand the thinking process behind bias correction. In this file, Data.gov is used to correct CMORPH for us to get CDF. The CDF values are then input into mMatLab program to get R0.01%

To apply bias correction, use IBICUS package in python
an example of using CMORPH to correct V3 projection dataset can be found in projection_correction 