# 網頁設計課程 -- 筆記、習題與專案

欄位 | 內容
-----|--------
學生 | 陳怡霖 
學號末兩碼 | ３８
教師 | 陳鍾誠
學校 | 金門大學
科系 | 華語文學系
我的專案 | 說明(myproject.md)

我的專案說明
個人網頁 :https://ar60110.github.io/wd107b/myproject.html

功能:

1.下拉式選單： 
功能：鼠標移至按鈕時，可產生數個按鈕連結到其他網站
<div class="navbar">
 <a href="#home">基地</a>
 <a href="#news">新消息</a>
 <div class="dropdown">
 <button class="dropbtn" onclick="myFunction()">必殺技祕笈
   <i class="fa fa-caret-down"></i>
 </button>
 <div class="dropdown-content" id="myDropdown">
   <a href="https://ar60110.github.io/wd107b/survey.html">加入足球社</a>
   <a href="#">贊助比賽</a>
   <a href="https://line.me/ti/p/wLWr6CluxX">聯絡資訊</a>
 </div>
2.側欄： 
功能：鼠標移至側欄時，可讓原先寬度較小的側欄變寬
在css裡寫出側欄屬性，用hover在html裡用和div呈現。

<div class="sidebar">
<ul>
<li><a href="#">閃電十一人</a></li>
<li><a href="https://ar60110.github.io/wd107b/canvas.html">我是畢卡索</a></li>
<li><a href="#">必殺技欣賞</a></li>
<li><a href="#">春天的氣息</a></li>
<li><a href="https://www.youtube.com/watch?v=4MtuBHDjXek">雷門歌王</a></li>
<li><a href="https://www.youtube.com/watch?v=GkdTlrUi4sk">舞王就是我</a></li>
</ul>
</div>
3.超連結載入圖片： 
運用<a href="連結前往的網址"><img src="圖片網址" width="200" height="100"></a>可以連結與設定圖片的長度與寬度。
<h3>    </h3>
<p><a href="https://chuuuuui.pixnet.net/album/photo/17066768-%e7%9a%87%e5%b8%9d%e4%bc%81%e9%b5%9d%e4%ba%8c%e8%99%9f.jpg"><img src="https://pic.pimg.tw/chuuuuui/1323870683-4001958127.gif"width="300" height="250"></a> </p>

4.連結至網站:
<a href="連結前往的網址"></a>可以連結去那個網站。
<a href="https://www.youtube.com/watch?v=4MtuBHDjXek">雷門歌王</a>
5.線上繪圖板： 
https://ar60110.github.io/wd107b/canvas.html
6.問卷表單:
表單可以做調查，可以勾選、填寫、輸入和送出。
網頁:https://ar60110.github.io/wd107b/survey.html
程式碼:<h4>徵人啟事</h4>
       <table width="500" height="300">
       <form name="myForm" action="demo_form.php"
      onsubmit="return validateForm()" method="post">
       名字: <input type="text" name="fname">
      <input type="submit" value="提交">
      </form>
      <form method=POST action=formTest.jsp>
        性別：
        男 <input type="radio" name="sex" value="boy" >
        女 <input type="radio" name="sex" value="girl"checked>
       未知<input type="radio" name="sex" value="none"checked><p>
   <p>
       級別：<input type="text" name="level" size=10><p>
      查克拉屬性:<input type="text" name="chakura"><p>
      才藝：
       <input type=checkbox name=check value=Godzilla>無敵破壞王
       <input type="checkbox" name="check" value="hāremumono king">後宮王
       <input type="checkbox" name="check" value="Chuunibyou ">中二病
       <input type="checkbox" name="check" value="Bancho">番長
       <input type="checkbox" name="check" value="pervert and change">  變態與變身
<p>
       能力值(請自行輸入，因為服務人員跑路中)：<br>
        <textarea name="talk" cols="50" rows="10"></textarea><p>
       您想應徵什麼職位?：
       <select name="want">
       <option value="隊長">地球保衛隊隊長
       <option value="使者">地獄來的使者
       <option value="角色">超真實扮家家酒的角色
       <option value="美少女">變成美少女拯救宇宙
       <option value="路人">異世界勇者身旁的路人乙
       <option value="下忍">史上最強下忍
        <option value="麻瓜">貴族麻瓜
       </select><p>
      <input type="submit" value="封印">
      <input type="reset" value="通靈術">
</form>

7.表格:
表格可以用來整理東西，使東西更清晰。
程式碼:
<table border="1" style="color:Gray;">
<tr>
  <td colspan="2">陳怡霖Yi Lin Chen</td>
</tr>
<tr>
　<td>生日</td>
　<td>９月１４日</td>
</tr>
<tr>
  <td>科系</td>
　<td>華語文學系</td>
</tr>
<tr>
  <td>出生地</td>
　<td>Tainan,Taiwan</td>
</tr>

<tr>
  <td>興趣</td>
  <td>Anime、Write novels、Music、Painting</td>
</tr>
<tr>
  <td>聯絡資訊</td>
  <td>ar60110@gmail.com</td>
</tr>
　
	
</table>

