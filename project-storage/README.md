# 研究專案本機儲存資料夾

請在網頁左側「研究專案」按「儲存研究專案」後，選擇這個資料夾。

儲存後會產生 JSON 檔：

- 每個研究專案各自一個 `project-...json`
- 全部研究專案最新總檔 `_thesis-workbench-latest.json`

上傳圖片會另外寫入：

- `imgData/`

同時也會保留在 JSON 的：

- `project.sources[].imageData`
- `images[].imageData`

圖目錄中的 `X` 只會刪除圖目錄項目，不會刪除 `imgData/` 裡的圖片檔。

這個資料夾只需要 `imgData/` 這一層圖片資料夾，不需要再建立更多巢狀子資料夾。
