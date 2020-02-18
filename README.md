# 2019-nCoV Data of Hubei Province


This repository provides **ready-to-use** data on daily confirmed, cured, and dead counts **grouped by cities** of Hubei province, which is the center of the [2019-nCoV](https://en.wikipedia.org/wiki/2019–20_Wuhan_coronavirus_outbreak) outbreak. It is continuously updated with the most recent data. Please cite the source for public uses.



## Details

**Raw data** is in folder [`csv_data`](https://github.com/cissieAB/2019-nCoV_Hubei_csv_Data/tree/master/csv_data) with names of `hubei_yyyy_mm_dd.csv`. Click [hubei_2020_02_06.csv](https://github.com/cissieAB/2019-nCoV_Hubei_csv_Data/blob/master/csv_data/hubei_2020_02_06.csv)  to preview.

- Data is getting with a third-party API: https://lab.isaaclin.cn/nCoV/, where the source is [Ding Xiang Yuan](https://ncov.dxy.cn/ncovh5/view/pneumonia). 

- Data is formed as tables and is sorted by city names.

- Data fields include confirmed, current confirmed (optional), cured and dead counts. Suspected counts is no longer available on [Ding Xiang Yuan](https://ncov.dxy.cn/ncovh5/view/pneumonia).

  > current confirmed = confirmed - cured - dead

- After 2020 Feb 08, data is pushed at a specific time every day. Before that, the most recent record is uploaded if there are multiple records of the same day. 



### Usage

You can create the city-based data of other provinces with [the sample code]().



## Acknowledgement

1. [DXY-2019-nCoV-Crawler](https://github.com/BlankerL/DXY-2019-nCoV-Crawler): https://github.com/BlankerL/DXY-2019-nCoV-Crawler

   



## Todo

- [ ] Add historical data
- [ ] Add sample code
- [ ] Polish README



