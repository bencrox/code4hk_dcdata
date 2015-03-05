# code4hk_dcdata
Simple data api for District Council, for CODE4HK

嘗試針對年期做一個簡單 API

http://api.somewhere/dc_y2011/member_by_dist.json/distcode/distname/membname?dist=taipo

第一粗分：選舉類別和年期 , dc_y2011 即 2011 ~ 2015 年度區選

第二粗分：資料類別，如以選區列議員： member_by_dist

第三粗分：資料格式，json, csv, tsv, xml, table ....

選項：指定列出甚麼資料，並以第一、二類資料作排列﹐不下選項即列出全部相類資料

過濾器：指定只挑甚麼資料　如 dist=taipo ，只列大埔的資料

用甚麼 database: mongo / redis 都試試就好。

上載資料要做 history / rate limit 以防災和防濫灌。history 宜可以 comment ，dump 了 data 可以 git 上載

上載者要申請 token 以便管理
