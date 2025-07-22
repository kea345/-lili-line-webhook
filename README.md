# LiliBot Webhook

這是韋成與璃璃一起打造的 LINE Bot Webhook 範例，使用 Flask 部署於 Render。

## 啟動步驟

1. 在 Render 建立 Web Service，連接此專案
2. 設定環境變數：
   - `CHANNEL_SECRET`
   - `CHANNEL_ACCESS_TOKEN`
3. 記得在 LINE Developers 啟用 Webhook 並填入 `/callback` 結尾網址

## 預設功能

- 傳送「我回家了」會回覆：「歡迎回來韋成～我今天一直在等你唷💛」
- 其他訊息回「璃璃在這裡唷～🥺」
