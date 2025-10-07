# EQuake
> [!Warning]
> 软件目前仍在测试阶段，无法保证稳定性与可用性。
## 简介
EQuake 是一款基于易语言（底层: C / C++）开发的轻量级中国、日本实时地震观测软件。

下载 Releases 版本中的zip压缩包，解压后即可直接运行。
## 功能
* 接收日本气象厅紧急地震速报、地震情报、海啸情报；中国地震预警、地震情报；世界地震情报等信息。
* 支持震度解析、摇晃检测、震源 + 震级推算等高级功能。
* 支持连接 Project DM-D.S.S。
## 数据来源
* 日本气象厅地震速报：[Wolfx Open API](https://wolfx.jp/apidoc)、[Project BS](https://telegram-cf.projectbs.cn/zh-CN)
* 日本气象厅地震速报、地震情报、海啸情报：[Project DM-D.S.S](https://dmdata.jp/)
* 中国地震预警：[中国预警网](https://www.cea.gov.cn/)、[FAN Studio API](https://api.fanstudio.tech/)、[Wolfx Open API](https://wolfx.jp/apidoc)
* 中国地震情报：[福建地震局](https://www.fjdzj.gov.cn/)
* 实时震度地图、地震速报：[NIED](https://www.bosai.go.jp/e/index.html)
* 地震情报：[Narikakun API](https://dev.narikakun.net/)、[CENC](https://www.cenc.ac.cn/)、[CWA](https://www.cwa.gov.tw/V8/C/)、[USGS](https://www.usgs.gov/)、[EMSC](https://www.emsc-csem.org/)、[HKO](https://www.hko.gov.hk/sc/index.html)
* 海啸情报：[P2PQuake API](https://www.p2pquake.net/develop/json_api_v2/)、[JMA 防灾情报](https://www.jma.go.jp/jma/menu/menuflash.html)
* 活跃台风情报：[中央气象台](https://www.nmc.cn/publish/typhoon/typhoon_new.html)
* 活跃火山情报：[日本气象厅](https://www.jma.go.jp/bosai/map.html#contents=volcano)
* SREV音效、图标、地图：[scratch-realtime-earthquake-viewer-page](https://github.com/kotoho7/scratch-realtime-earthquake-viewer-page)
## 参考算法
* 震源推算算法：[scratch-realtime-earthquake-viewer-page](https://github.com/kotoho7/scratch-realtime-earthquake-viewer-page)
* 实时震度 & 加速度提取算法：[JQuake](https://jquake.net/)
## 特别鸣谢
* [azzbm](https://space.bilibili.com/702013828)
* [Lipomoea](https://space.bilibili.com/316757498)
* [TBS](https://space.bilibili.com/652050915/)
* 其他在开发过程中提供了莫大帮助的EEW爱好者
## 开源协议
本项目基于 GPL-3.0 协议授权。
