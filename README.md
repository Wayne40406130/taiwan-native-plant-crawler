# taiwan-native-plant-crawler
This repository contains a web crawler designed to fulfill the requirements outlined for crawling data from the specified [臺灣本土植物數位化典藏](https://sinica.digitalarchives.tw/collection.php?type=3799).

## Requirements
- crawl data from this url: https://sinica.digitalarchives.tw/collection.php?type=3799
（only 臺灣本土植物數位化典藏）
  - can save data as json files or to a database, such as sqlite(bonus)
  - properties we need: 
    - 中文種名(string)
    - 學名(string)
    - 標本館號(string)
    - 編目號(string)
    - 引用(string)
    - 採集日期(date string)
    - 採集者(string)
    - 緯度(float)
    - 經度(float)
    - 國家(string)
    - 行政區(string)
    - 最低海拔(float)
    - image url(string)
