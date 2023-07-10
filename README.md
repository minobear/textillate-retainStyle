# textillate-retainStyle
原始版本的 textillate.js 無法保留原先對個別文字所設定的style、class、id，這個版本將能夠保留並順利呈現於動畫後的文字上!

## 舉例:
  ```html
  這是一段 <span style="color:red;">測試</span> 文字
  ```
- 原先無保留樣式的版本:
  使用textillate讓文字動畫後，"測試"兩個字的紅色樣式將不見。
- 此版本的效果:
  使用textillate讓文字動畫後，"測試"兩個字紅色樣式依舊存在；同時包括class、id的設定也會被保留。
