# τQuake

![Tauri](https://img.shields.io/badge/Tauri-Desktop_App-24C8DB?logo=tauri&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-Build_Tool-646CFF?logo=vite&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-3A7BD5)

一个使用 **Tauri + Vite.js** 构建的地震预警可视化工具。  

> [!WARNING]
> 当前版本为公测版。
> 可能存在功能不完整、兼容性问题或稳定性波动，请勿将本软件作为唯一预警依据。



## 功能
- 接收日本气象厅地震预警速报、台湾省中央气象署、中国地震台网地震预警速报

## 支持平台
- Windows
- macOS
- Linux

具体可下载安装的系统版本与架构请以 Releases 页面提供的安装包为准。


## 下载安装
1. 前往 Releases 页面下载最新版本安装包。
2. 安装完成后启动 τQuake。

## 数据来源
### Wolfx API
- 地震预警：CEA / SC / FJ / CWA / JMA
- 地震订阅：CENC / JMA
- IP 定位

文档地址：<https://wolfx.jp/apidoc>

### FAN Studio API
- 地震预警：CEA
- 地震订阅：CENC / USGS / JMA

文档地址：<https://api.fanstudio.tech/>

### 语音素材
- 英语倒计时素材：Microsoft Azure Text-to-Speech

参考文档：<https://docs.azure.cn/zh-cn/ai-services/speech-service/text-to-speech>

## 鸣谢
感谢以下开源项目提供思路、实现参考与灵感：

- [TREM-Lite](https://github.com/ExpTechTW/TREM-Lite)
- [scratch-realtime-earthquake-viewer-page](https://github.com/kotoho7/scratch-realtime-earthquake-viewer-page)
- [要石 kanameishi](https://github.com/Lipomoea/kanameishi)
- [CNQuake2](https://github.com/liujh5913/CNQuake2)

## 免责声明
本项目提供的信息仅用于学习、研究与辅助参考，不构成任何官方灾害预警依据。  
请以当地官方发布的地震预警与应急通知为准。
