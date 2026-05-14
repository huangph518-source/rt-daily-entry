# 呼吸治療組 每日業務量填寫

行動版單檔表單，給組員在手機/電腦填寫當日業務量。

- 本地表單畫面：自動帶今日日期，選擇姓名後填 5 項數值
- 送出路徑：透過 Power Automate Webhook 寫入 OneDrive 上的主檔 Excel
- 無 Webhook 時：自動把該筆資料複製成文字，可貼到 LINE/Email 給主管

部署：GitHub Pages（自動由 main branch root 發佈）。
