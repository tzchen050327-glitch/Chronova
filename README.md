# Chronova 星際日曆

手機優先的繁體中文離線行程日曆。支援月曆、週曆、日程與行程列表、分類、搜尋、主題切換、JSON 備份及還原。

## 網站與部署

GitHub Pages 網址（需成功部署後才會開啟）：
https://tzchen050327-glitch.github.io/Chronova/

首次啟用：開啟儲存庫 **Settings → Pages → Build and deployment → Source → GitHub Actions**。接著在 **Actions** 頁面確認「Deploy Chronova」工作流程執行成功。若未自動執行，可手動執行 workflow_dispatch。

## 在 Android 安裝

用 Chrome 開啟上方網站，點選瀏覽器選單「安裝應用程式」或「新增至主畫面」。安裝選項會依瀏覽器對 PWA 的檢測結果而有所不同。

## 注意事項

- 行程存放在本機 localStorage，**不會自動同步**到其他手機或 Google 日曆。
- 建議定期透過「匯出備份」儲存 JSON 檔。
- 無網路時可使用先前已成功快取的頁面。
- 此版本**不包含**背景推播通知、原生 Android 桌面小工具、農曆或雲端同步。
