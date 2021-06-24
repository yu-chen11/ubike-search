# YouBike 搜尋系統

###### 此搜尋系統提供查詢臺北YouBike、Youbike2.0、新北YouBike、桃園YouBike各站點剩餘車數

## 專題說明

### 設計背景

由課程作業 **桃園公共自行車即時服務資料** 發想，當時課程作業成果設計為輸出於consloe，且資料更是只有經過簡單分類，對使用者非常不便。  
因此想設計對使用者較為友善的介面，延伸出增加臺北市、新北市UBike資料API，可查詢各個站點剩餘車數以及連結Google Map查詢站點位置，並以視窗呈現內容。

### 設計目的
1. 改善使用者使用經驗
1. 設計友善使用者的介面
1. 圖像化站點車輛資訊
1. 簡化使用者操作

## 專題介紹
### Requirement
```python
import random
import tkinter
from tkinter import *
import requests
import webbrowser
```
