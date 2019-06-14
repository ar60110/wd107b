網誌說明:

1.下拉菜單
功能:
可連入問卷調查及製作者的通訊軟體帳號。
使用技術:
<div class="dropdown">
 <button class="dropbtn" onclick="myFunction()">
 

2.側邊欄
功能:
點選內容能連結至該網站，滑鼠一致側欄時，側欄會變寬，移走時則會縮小。
使用技術:

<div class="sidebar">
<ul>


3.利用超連結插入圖片：
功能:
利用語法加入圖片，並且設定圖片的長度與寬度。
使用技術:
<a href="連結前往的網址"><img src="圖片網址" width="" height=""></a>

圖片的置中方法與文字整理在頁面中間
div style="text-align: center"


4.問卷調查
功能:
可以選擇及填寫各種資料，但是送出後會沒有回應。
使用技術:
1.使用者可以由 type="text" 的輸入欄位進行打字輸入

2.<input type="submit" value="提交">可以提交使用者的名字

3.有許多像選項按鈕，大多能夠複選。



5.小繪圖板
功能:能夠在上面畫圖
使用技術:

var canvas = document.getElementById("myCanvas");
var ctx = canvas.getContext("2d");

