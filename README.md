# NPI-Q SUMMARY — GitHub Pages 更新版

此版本沿用原本 12 項 NPI-Q 表格及 English Summary 的計算邏輯。

## 本次更新
- 英文欄位標題與症狀名稱放大，視覺設計調整為柔和的醫療專業風格。
- Checkbox 與 Radio Button 從 23px 縮小為 18px，仍保留整格可點選。
- 新增下方「診斷書文字生成」區塊，提供心智測驗日期與 CDR 分數欄位。
- 診斷書文字自動帶入 Severity Total 與 Caregiver Distress Total；調整量表時即同步更新。
- 新增 Copy Certificate Text，一鍵複製診斷書段落。
- Reset 同步清除日期、CDR、兩個報告以及量表選取。

## GitHub Pages 上傳
1. 解壓縮 ZIP。
2. 開啟 `cscins3/npiq-summary-test-version` GitHub repository。
3. 將 `index.html` 上傳至原本網站所在目錄，覆蓋舊版並 Commit。
4. 若網站仍是舊畫面，稍待 GitHub Pages 部署並強制重新整理瀏覽器。

## 診斷書產生規則
`該病患因上述疾病於本院追蹤，於YYYY年MM月DD日心智測驗報告CDR為X分。NPIQ量表：疾病嚴重度A分，照顧者負荷B分`

- A = Severity Total
- B = Caregiver Distress Total
- 日期與 CDR 未填寫時，顯示待填佔位文字，不自動推測病患資訊。

使用前請由醫療人員確認內容與評分。所有資料僅在瀏覽器本機處理，無外部服務與第三方程式庫。
