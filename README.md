# What I Read Today
> 我今天讀了什麼

## 緣起

**突然**想要記一下自己每天在電腦(或手機，如果有記得記)上讀了哪些東西，  
能列入的標準由我自己決定，大概長度到一個門檻就可能會列入，  
可能是網站文章、可能是網路影片、也可能是社群媒體發文，  
列表不分領域，大略以閱讀完成時間排序。暫定按月分檔案。

- [2016-12](2016-12.md)
- [2017-01](2017-01.md)
- [2017-02](2017-02.md)
- [2017-03](2017-03.md)

## 圖例

- 這是一個項目
  - 這是那個項目的補充說明
  - 如果還有第二項之後也是補充說明

## 輔助

我用以下這個 bookmarklet 產生一個包含 `document.title` 和 `window.location` 的 markdown 無序列表項目方便我複製貼上。  
可以在書籤列建立一個新的書籤，以這段語法當作他的網址，之後就可以直接點擊使用。  
目前發現 GitHub 和 Twitter 會出現 `Content Security Policy: 頁面的設定阻擋了 self 的資源載入` 錯誤，無法使用 bookmarklet 會有點困擾，只能打開 console 自己複製 title。

```
javascript:(function(){var%20title=document.title;var%20href=window.location;window.prompt('','-%20['+title+']('+href+')');})();
```
