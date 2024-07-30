# Data Acquisition

Welcome to Data Acquisition where we attempt to reduce the painful process of obtaining data but we all know I write unreadable codes so gudluck

Available data you can get:
---------------------------------------------------------------------------------------------------------
| Dataset    | Temporal  resolution    | Spatial resolution   | Type           | Varible name  | Units    |
| -----------| ----------------------- | -------------------- | -------------- | ------------- | -------- |
|  NEA       | Daily                   |  Point               | Rain gauge     | Precipitation | mm /day  |
| -----------| ----------------------- | -------------------- | -------------- | ------------- | -------- |
|  Data.gov  | 5 minute                |  Point               | Rain gauge     | Precipitation | mm /5min |
| -----------| ----------------------- | -------------------- | -------------- | ------------- | -------- |
|  IMERG     | 30 minutes              | 10km x 10km          | Satellite      | precipitation | mm /hr   |
| -----------| ----------------------- | -------------------- | -------------- | ------------- | -------- |
|  GSMaP     | Hourly                  | 10km x 10km          | Satellite      | precipitation | mm /hr   |
| -----------| ----------------------- | -------------------- | -------------- | ------------- | -------- |
|  CMORPH    | 30 minutes              | 8km x 8km            | Satellite      | cmorph        | mm /hr   |
| -----------| ----------------------- | -------------------- | -------------- | ------------- | -------- |
|  ERA5      | Hourly                  | 27km x 27km          | Reanalyzed     | pr            | mm /hr   |
| -----------| ----------------------- | -------------------- | -------------- | ------------- | -------- |
|  ERA5_Land | Hourly                  | 9km x 9km            | Reanalyzed     | pr            | mm /hr   |
| -----------| ----------------------- | -------------------- | -------------- | ------------- | -------- |
|  CHIRPS    | Daily                   | 5km x 5km            | Satellite      | precipitation | mm /day  |
| -----------| ----------------------- | -------------------- | -------------- | ------------- | -------- |

Steps:
1) Open the Jupyter notebook for the dataset that you want and follow instructions run code
2) Extract data using Data Extraction folder

*For chirps, it is advised to download directly from https://data.chc.ucsb.edu/products/CHIRPS-2.0/global_daily/netcdf/p05/
