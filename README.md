# 91APP 後台快速編輯選單

一個方便的 Tampermonkey 腳本，讓你可以在 91APP 商店前台快速跳轉到對應的後台編輯頁面。

## 功能特色

- 在商店前台頁面右上角新增可拖曳的編輯選單
- 自動判斷當前頁面類型（商品頁/文章頁），顯示對應的編輯按鈕
- 快速跳轉功能：
  - 編輯當前頁面
  - 前往部落格文章總覽
  - 前往頻道頁總覽
- 支援拖曳移動選單位置
- 美觀的使用者介面與動畫效果

## 安裝方式

1. 安裝 [Tampermonkey](https://www.tampermonkey.net/) 瀏覽器擴充功能
2. 點擊 [安裝腳本](#) (等待發布後新增連結)
3. 安裝完成後設定要套用的網域：
   - 點擊 Tampermonkey 圖示
   - 選擇「管理面板」
   - 找到「91APP 後台快速編輯選單」腳本
   - 點擊「編輯」
   - 在 `// @match` 後方修改為你的網域，例如：
     ```
     // @match        https://你的網域/*
     ```
   - 按下 Ctrl+S 儲存

## 使用說明

- 完成網域設定後，進入商店前台頁面時右上角會出現編輯選單
- 在商品頁或文章頁時，點擊「編輯此頁」可直接跳轉至對應的後台編輯頁面
- 點擊下拉箭頭可展開更多功能選項
- 按住選單左側的拖曳圖示可移動選單位置

## 版本紀錄

### v1.0.0
- 初始版本發布
- 實現基本編輯功能
- 新增可拖曳介面
- 支援自訂網域

## 授權

MIT License

## 作者

[李元魁](https://www.linkedin.com/in/seo-circleghost/)

## 問題回報

如果發現任何問題或有功能建議，歡迎在 GitHub 提出 Issue。
