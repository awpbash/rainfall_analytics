## Data manipulation

Data Comparison allows users to compare trends and patterns across various datasets. Just manually add the data variables at every step.

*Important to adjust the units accordingly for **high-frequency analysis** ie. Data.gov provides 5-minute data so x 12 to obtain hourly rainfall.


Bias_correction allows users to see and understand the thinking process behind bias correction. In this file, Data.gov is used to correct CMORPH for us to obtain the cumulative distribution function. The bias correction process utilizes the Ibicus python package.

The CDF values are then input into the MatLab program provided by ITU 837 Annex 2 to obtain R0.01% at 1 minute integration time.


An example of bias correction on future data is shown in projection_correction notebook where data from CMORPH 2010 - 2014 is used to bias correct CCRS V3 data to obtain a transfer function and applied to CCRS V3 projection from 2040 - 2045. 

***It is assumed that CMORPH is "ground truth" in this scenario though further investigation and correction with rain gauge data may be necessary.***


Reference:
1) Ibicus package: https://ibicus.readthedocs.io/en/latest/getting_started/overview.html
2) MSS V3 dataset technical reports: https://t432-p683-blue.prd.cwp2.sg/v3-climate-projections/resources/v3-reports

