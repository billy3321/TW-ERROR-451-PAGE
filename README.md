#台灣HTTP ERROR 451抗議財智局頁面

為了使各單位重視，我們來做一個ERROR 451的Blackout頁面吧，起個頭，讓大家可以改得漂亮一點。

##為何是ERROR 451

HTTP ERROR 中，最常見到的是 ERROR 404，也就是網站上沒有你輸入網址的網頁。而 ERROR 451，是 2012 年五月時，XML 規格的創始作者、現在 Google 員工 Tim Bray 所提出的新錯誤碼。當英國政府下令網路服務提供者阻擋海盜灣（The Pirate Bay）時，一般阻擋工具最常回傳的 ERROR 403：禁止閱覽，而他希望 ERROR 451 能更明確說明該網頁禁止閱覽的原因，是受到國家法律而進行封鎖。至於為什麼選擇 451，就是要和 Ray Bradbury 的《華氏 451 度》致敬。
--參考資料： http://binb.tw/?p=407

##如何套用到blog

以blogspot為例，請參考相關文章了解模版修改基本知識
http://hakashyu.blogspot.com/2011/10/blog-post_16.html

接著，請看 error_451.htm 網頁。

把第8行到第87行的內容複製下來（從`<!-- freeandopen head -->`到`<!-- freeandopen head -->`），貼到模版裏面的head區塊。
把第91行到第103行的內容複製下來（從`<!-- freeandopen body -->`到`<!-- freeandopen body -->`），貼到模版裡的body區塊。

儲存模版以後就OK了。

往後要刪除也很簡單，把`<!-- freeandopen head -->`及`<!-- freeandopen body -->`中間的區塊刪除就好了。
