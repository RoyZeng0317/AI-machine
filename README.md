## 基本介紹
這是一款使用 Arduino IDE 進行開發的 AI 對話機器人
目前採用的是 Claude Code 的 AI 模型進行對話
語言有中文與英文可供選擇進行交流

## 韌體體需求

| 韌體名稱 | 版本需求 |
| --- | --- |
| Arduino ESP32 | 任一版本皆可 |
| 麥克風模組| INMP441 |
| 螢幕 | I2C OLED |
| PowerShell | Winodws 10 、 11等電腦 |

## 接線圖

[img]

## 安裝教學
**安裝前需要注意 Aruino.ino 的 Wi-Fi  SSID: "你的 Wi-Fi 名稱" 與 Wi-FI PASSWORD: "你的 Wi-Fi 密碼" 都需要更改**
```bash
git clone https://github.com/RoyZeng0317/AI-machine
cd AI-machine
install
```


## 基本問題
```bash
```**Q:為什麼安裝後不能使用
A: 確認是否有有輸入 cd AI-machine 進入資料夾進行安裝
**```
```**Q:我的ESP32 是 Type-C 版的但是為什麼不能燒入?***
A:如果你是在蝦皮購買的產品，並且是有兩個 Type-C port 的部分
分別為 OTG port 與 TTL port
點下方連結進行安裝 OTG 驅動程式
https://
**```
```

下列是查尋到的 ESP32 開發版可以使用的驅動程式

| Arudino ESP32 開發版 | 橋接晶片 | 是否需要驅動程式 |
| --- | --- | --- |
| Arudino ESP32-S3-CAM | CJ340 | 是 |
| Arudino ESP32-CAM (AI Thinker) | CH340 | 是 |
| Arduino ESP8266 NodeMCU v1 | CH340 | 是 |
| Arduino XIAO ESP32-S3 | 原裝 USB | 是 |
| Arduino ESP32 nano | 原生 OTG USB | 否 |
| Arduino ESP32 DevKit | CP102 | 否 |
| Arduino ESP32-S3 DevKit | 原生 OTG USB | 否 |

***總結: 如果你的 ESP32 開發版有 OTG port 與 TTL port 兩個的話皆需要驅動程式進行安裝***
