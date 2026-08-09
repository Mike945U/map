# 校內處室查詢

## 主要維護方式
1. 用 Excel 開啟 `offices.csv`。
2. 新增一列：處室名稱、空間編號、建築物、樓層、樓層圖片。
3. 把新大樓的樓層圖放到 `maps/大樓代碼/`。
4. 樓層圖片欄填入相對路徑，例如 `maps/AD/2F.jpg`。
5. 若有校園配置圖，命名為 `campus.jpg` 放在 `maps/`。

## 注意
因瀏覽器安全限制，直接雙擊 index.html 時 fetch CSV 可能無法讀取。
上傳 GitHub Pages 後即可正常使用；本機測試可用簡易 HTTP server。
