# Image Overlay Effects 圖片覆蓋效果

![home](https://i.imgur.com/iMKT1N6.png)

## Demo

https://vii120.github.io/image-overlay/


## Intro

使用**css transition**做出滑鼠hover後不同的圖片覆蓋動畫效果

主要覆蓋效果有fade in / slide in / zoom in&out

### Fade in 

淡入效果，純文字覆蓋效果分別用了偽元素(pseudo class)及區塊(div)兩種不同方式做出相同效果

按鈕覆蓋效果的半透明背景，分別用了濾鏡處理(filter)及可透視區塊(div)兩種不同方式做出相同效果

![fade](https://i.imgur.com/U9yb1dj.png)

### Slide in

滑入效果，分別有上下左右、斜角方向及中心點向外擴散

最後一個**two step from center**是想嘗試做出映像管電視開關時的畫面效果

![slide](https://i.imgur.com/yhCwtbS.png)

### Zoom

放大(zoom in)及縮小(zoom out)效果，亦有雙圖片切換範例(zoom with two images)

![zoom](https://i.imgur.com/UVA0FqL.gif)

## CSS preprocessor

使用**SCSS**撰寫

## Reference

W3School：[CSS Styling Images](https://www.w3schools.com/css/css3_images.asp)
