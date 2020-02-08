# 2019-nCoV Data of Hubei Province


This ongoing project provides **ready-to-use** data on daily confirmed, cured, and dead counts **grouped by cities** of Hubei province, which is the origin of the [2019-nCoV](https://en.wikipedia.org/wiki/2019–20_Wuhan_coronavirus_outbreak) outbreak. Please cite the source for public purpose.



## Explanation

### Raw data

Raw data is in folder [`csv_data`](https://github.com/cissieAB/2019-nCoV_Hubei_csv_Data/tree/master/csv_data) with names of `hubei_yyyy_mm_dd.csv`. Click [hubei_2020_02_06.csv](https://github.com/cissieAB/2019-nCoV_Hubei_csv_Data/blob/master/csv_data/hubei_2020_02_06.csv)  to preview the data.



### Details

The provided data is getting with a third-party API: https://lab.isaaclin.cn/nCoV/, where the source is [Ding Xiang Yuan](https://ncov.dxy.cn/ncovh5/view/pneumonia). 

As the suspected count is no longer open to the public, the raw data contains confirmed, cured and dead counts only. Data is formed as tables and is sorted by city names. The most recent record is logged if there are multiple records for the same day. 



### Usage

You can create the city-based data of other provinces with [the sample code]().





## Reference

1. [DXY-2019-nCoV-Crawler](https://github.com/BlankerL/DXY-2019-nCoV-Crawler): https://github.com/BlankerL/DXY-2019-nCoV-Crawler
2. [DXY-2019-nCoV-Data](https://github.com/BlankerL/DXY-2019-nCoV-Data): https://github.com/BlankerL/DXY-2019-nCoV-Data



## Todo

- [ ] Add historical data
- [ ] Add sample code
- [ ] Polish README



