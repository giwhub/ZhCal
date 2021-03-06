# 農曆工具包

* 作者：[910JQK](https://github.com/910JQK/zhcal)

* 用法：

* 傳統中文用戶

* 參數：

m: 月<br>
y: 年<br>
n: 現在<br>
i: 信息<br>
f: 節日

## 農曆日曆

```
$ zhcal 
                            十月 2015                            

   週一     週二     週三     週四     週五     週六     週日  

                            1 十九   2 二十   3 廿一   4 廿二  
 5 廿三   6 廿四   7 廿五   8 寒露   9 廿七  10 廿八  11 廿九  
12 三十  13 九月  14 初二  15 初三  16 初四  17 初五  18 初六  
19 初七  20 初八  21 重陽  22 初十  23 十一  24 霜降  25 十三  
26 十四  27 十五  28 十六  29 十七  30 十八  31 十九  

$ zhcal m 2015 2
                            二月 2015                            

   週一     週二     週三     週四     週五     週六     週日  

                                                       1 十三  
 2 十四   3 十五   4 立春   5 十七   6 十八   7 十九   8 二十  
 9 廿一  10 廿二  11 小年  12 廿四  13 廿五  14 廿六  15 廿七  
16 廿八  17 廿九  18 除夕  19 春節  20 初二  21 初三  22 初四  
23 初五  24 初六  25 初七  26 初八  27 初九  28 初十  
```

## 四柱查詢

```
$ zhcal n

西元 2015 年 10 月 5 日  週一
農曆 八月廿三  生肖：羊
四柱 乙未年  乙酉月  甲寅日  甲戌時
時間 東八區 20 時 46 分 14 秒  正三刻

$ zhcal i 2015 1 1 0

西元 2015 年 1 月 1 日  週四
農曆 冬月十一  生肖：馬
四柱 甲午年  丙子月  丁丑日  庚子時
時間 東八區 0 時 0 分 0 秒  正初刻
```

## 節日查詢

```
$ zhcal f 2014
臘八 臘月初八   1 月  8 日  週三
小年 臘月廿三   1 月 23 日  週四
除夕 臘月三十   1 月 30 日  週四
春節 正月初一   1 月 31 日  週五
元宵 正月十五   2 月 14 日  週五
上巳 三月初三   4 月  2 日  週三
端午 五月初五   6 月  2 日  週一
七夕 七月初七   8 月  2 日  週六
中元 七月十五   8 月 10 日  週日
中秋 八月十五   9 月  8 日  週一
重陽 九月初九  10 月  2 日  週四
重陽 九月初九  11 月  1 日  週六
下元 十月十五  12 月  6 日  週六

寒食  4 月  4 日  週五
清明  4 月  5 日  週六
夏至  6 月 21 日  週六
冬至 12 月 22 日  週一
```

* 简体中文用户

* 参数：

yl: 月历<br>
nl: 年历<br>
xz: 现在<br>
zd: 指定时间<br>
jr: 节日

## 农历日历

```
$ zhscal
                            五月 2017                            

   周一     周二     周三     周四     周五     周六     周日  

 1 初六   2 初七   3 初八   4 初九   5 立夏   6 十一   7 十二  
 8 十三   9 十四  10 十五  11 十六  12 十七  13 十八  14 十九  
15 二十  16 廿一  17 廿二  18 廿三  19 廿四  20 廿五  21 小满  
22 廿七  23 廿八  24 廿九  25 三十  26 五月  27 初二  28 初三  
29 初四  30 端午  31 初六  

$ zhscal yl 2017 5

                            五月 2017                            

   周一     周二     周三     周四     周五     周六     周日  

 1 初六   2 初七   3 初八   4 初九   5 立夏   6 十一   7 十二  
 8 十三   9 十四  10 十五  11 十六  12 十七  13 十八  14 十九  
15 二十  16 廿一  17 廿二  18 廿三  19 廿四  20 廿五  21 小满  
22 廿七  23 廿八  24 廿九  25 三十  26 五月  27 初二  28 初三  
29 初四  30 端午  31 初六  
```

## 四柱查询

```
$ zhscal xz

公元 2017 年 5 月 3 日  周三
农历 四月初八  生肖：鸡
四柱 丁酉年  甲辰月  庚寅日  癸未时
时间 东八区 13 时 6 分 0 秒  初初刻

$ zhscal zd 2017 4 5 18

公元 2017 年 4 月 5 日  周三
农历 三月初九  生肖：鸡
四柱 丁酉年  甲辰月  壬戌日  己酉时
时间 东八区 18 时 0 分 0 秒  正初刻
```

## 节日查询

```
$ zhscal jr 2017
腊八 腊月初八   1 月  5 日  周四
小年 腊月廿三   1 月 20 日  周五
除夕 腊月三十   1 月 27 日  周五
春节 正月初一   1 月 28 日  周六
元宵 正月十五   2 月 11 日  周六
上巳 三月初三   3 月 30 日  周四
端午 五月初五   5 月 30 日  周二
七夕 七月初七   8 月 27 日  周日
中元 七月十五   9 月  4 日  周一
中秋 八月十五  10 月  3 日  周二
重阳 九月初九  10 月 27 日  周五
下元 十月十五  12 月  1 日  周五

寒食  4 月  3 日  周一
清明  4 月  4 日  周二
夏至  6 月 21 日  周三
冬至 12 月 22 日  周五
