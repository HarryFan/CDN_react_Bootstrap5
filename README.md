# CDN_react_Bootstrap5
教學用CDN的方式引入react  bootstrap5 切版練習

# React 圖片卡片應用

這是一個使用React和Bootstrap 5製作的圖片卡片應用。

## 功能

- 顯示圖片卡片列表
- 每個卡片都有標題、圖片和鏈接

## 如何使用

1. 下載此代碼。
2. 打開 `index.html` 文件在瀏覽器中。
3. 您將看到圖片卡片列表。

## 依賴項

- React
- Bootstrap 5
- Babel

## 聯繫

如有任何問題或建議，請聯繫 [harris750110@gmail.com](mailto:harris750110@gmail.com)。


`$(document).ready()` 是 jQuery 中的一個常見方法，用於確保當 HTML 文檔完全載入且 DOM (Document Object Model) 樹建立完畢時，才執行裡面的 jQuery 代碼。換句話說，它確保你的 jQuery 代碼在文檔的所有元素都已經可用之後才運行，避免由於 DOM 元素尚未加載完畢而導致的錯誤。

基本語法如下：
```javascript
$(document).ready(function() {
   // 你的 jQuery 代碼
});
```

或者使用縮短的語法：
```javascript
$(function() {
   // 你的 jQuery 代碼
});
```

舉例說明，如果你希望在文檔加載完成後隱藏一個具有特定ID的元素，你可以這樣寫：

```javascript
$(document).ready(function() {
    $('#myElement').hide();
});
```

這段代碼的意思是：當文檔完全加載完成時，找到 ID 為 "myElement" 的元素並將其隱藏。如果沒有使用 `$(document).ready()`，這段代碼可能在 "myElement" 元素還沒有被載入到頁面上時就執行，導致隱藏操作失敗。
