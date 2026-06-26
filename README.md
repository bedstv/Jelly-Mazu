# Jelly-Mazu

馬祖景點地圖總覽的 GitHub Pages 互動版。

## 內容

- 南竿、北竿、東引景點與美食清單
- 地圖標記可點擊，會開啟 Google Maps
- 港口／碼頭快速連結
- 手機版響應式排版

## GitHub Pages 啟用方式

因為 GitHub Pages 的部署來源通常需要在 Repository Settings 內開啟，請到：

`Settings` → `Pages` → `Build and deployment`

選擇：

- Source：`Deploy from a branch`
- Branch：`main`
- Folder：`/ (root)`

儲存後，頁面網址通常會是：

https://bedstv.github.io/Jelly-Mazu/

## 更新方式

主要內容集中在 `index.html` 裡的 `places` 陣列。新增景點時，增加一筆資料即可：

```js
{ region: '南竿', type: 'food', no: 7, name: '店名', q: 'Google Maps 搜尋關鍵字' }
```
