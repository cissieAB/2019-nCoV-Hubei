# 2019-nCoV Data of Hubei Province


This ongoing project provides **ready-to-use** data on daily confirmed, cured, and dead counts **grouped by cities** of Hubei province, which is the origin of the [2019-nCoV](https://en.wikipedia.org/wiki/2019–20_Wuhan_coronavirus_outbreak) outbreak. Please cite the source for public purpose.



### Organization

#### Raw data

The raw data is in folder`csv_data` with names of `hubei_yyyy_mm_dd.csv`.

Click [hubei_2020_02_06.csv](https://github.com/cissieAB/2019-nCoV_Hubei_csv_Data/tree/master/csv_data)  to preview the data.



#### Implementation

The provided data is getting with a third-party API: https://lab.isaaclin.cn/nCoV/, where the source is [Ding Xiang Yuan](https://ncov.dxy.cn/ncovh5/view/pneumonia). 

As the suspected count is no longer open to the public, the raw data contains confirmed, cured and dead count only. Data is formed as tables and sorted by city names.

If there are multiple records for the same day, use the most recent record. 



### Reference

1. [DXY-2019-nCoV-Crawler](https://github.com/BlankerL/DXY-2019-nCoV-Crawler): https://github.com/BlankerL/DXY-2019-nCoV-Crawler
2. [DXY-2019-nCoV-Data](https://github.com/BlankerL/DXY-2019-nCoV-Data): https://github.com/BlankerL/DXY-2019-nCoV-Data



### Todo

- [ ] Add historical data
- [ ] Add sample code
- [ ] Polish README



