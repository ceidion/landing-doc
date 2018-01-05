# 如何有效率地 Google 尋找問題並學習新技術

當我就任三、四個月後，設計部專門負責網頁切版的大前輩離開了，知道這消息實在晴天霹靂，代表著這重責大任要落在我身上了。那時候我切出來的版型常被工程部吐槽，都會被碎念「啊你這版型不行啦，我程式沒辦法接」、「我這裡要跑重複資料，要 Repeat 的話 HTML 標籤要從哪裡 Copy 到哪裡？」、「你這 Layout 是要抓哪啊？你寫得真得很”巢”耶...我真的完全看不懂」。所以那時候每次將版型丟給後端那幾個小時都會如座針氈，深怕下一秒又被召喚過去吐槽。

我們公司大部分都承接系統開發，幾乎所有的網頁都會接成動態應用程式，程式語言跟資料庫是用 .NET + MSSQL，後端工程師的嘴雖然很會碎念，但對我這新人還是會耐著性子和我討論，那時常和我配合的工程師叫做阿杜，進來已經三四年了，整個就是一隻老鳥。

我：「所以你會切版嗎？要不然你教我幾招啊，你都會 .NET 了，HTML、CSS 應該還可以吧？」  
阿杜：「金拍謝...我會得還沒你多，你可能要自己多研究，以後公司靠你了，你是未來的棟梁。」  
我：「真的假的啊...哩賣騙肖..」  
阿杜：「真的，我在公司只負責動態程式跟資料庫邏輯而已，之前都設計部在負責，排版整個忘光！Google 有很多資料你多參考啦，我不會也是自己 Google 的！」

實在太哭爸了，我真的超級無言，每次阿杜要我自立自強解決問題時，都會靠北一句「以後公司靠你了，你是未來的棟梁，你可以的！！」來敷衍我，我就會很無言地回到座位上繼續解 IE6、7、8 的 Bug，彷彿大海撈針般從 Google 老師探索我想要找尋的答案。

講完我的故事，接下來就來分享一下自己如何用 Google 來解決問題吧。

## 學任何技能都是從模仿開始

我一開始在學習 HTML、CSS 時，基本的語法概念是有的，當我想要學得更深入時，去網路上看別人部落格，絕大部分都發現到會要你去 W3C 好好看過一遍再來開始學網頁排版。後來我也是照做了，但越做越想睡，雖然基礎知識有了，但我到底該如何運用這些標籤來設計出我要的網頁版型出來，整個就是毫無頭緒。而在當我學 jQuery、JS 時也有這樣的想法。

但一直重複地 Google 撞牆後，還是有發現到一些有用的學習方式。其中一個就是**去看別人寫的範例程式碼**，網路上不乏會有很多開發者分享自己做網頁版型的範例，裡頭的語法已經讓我有大概的印象，只要瞭解裡頭的語法，我也可以跟他做到一樣的事情，而這種方法也讓我開始改變學習方式，在一開始學新技術前，我會先去學一點基礎的語法，甚至買書來看。等到稍微有些小成就後，就開始去搜尋關鍵字找一些簡單的範例來吸收，有看不懂的語法就回頭翻書或 Google 加深觀念。那時我也會打「website template」、「網頁版型」之類的關鍵字，將別人做得很完整的範例整個看過一遍加深觀念。

沒有人天生就是天才，就像是給你關刀，你知道怎麼亂揮舞，但是刀是拿來斬人的，人會亂移動，你要有效率的斬人一開始是絕對沒譜的，自然就會想去看關公施展招式的過程中學個一招半式，然後自己再去練習怎麼斬，進而內化成自己的武功心法。

所以才會說一開始學新技術時，先瞭解一些基礎語法後，就從網路上尋找各種範例來練習吧。

## 先從自己看得懂得程式碼下手

既然要找範例，也記得要找自己稍微看得懂得東西來看。絕對不要找那種跟自己層次差太多的文章，只會讓自己的學習曲線變高，挫折感變重。

這觀念就有點像是高中在上微積分，老師在台上口沫橫飛，你完全聽不懂，舉手問老師，老師重新講解還是丈二金剛摸不著頭緒，於是只好請教隔壁的同學。同學因為和你的背景相似，比較瞭解你的程度，所以在口語解釋上你比較能聽懂他在講啥。

除了透過網路搜尋別人的開發部落格外，[GitHub](https://github.com/) 搜尋也是個好方法，它目前已經是世界最大的程式碼集聚地，例如說你想用 JavaScript 寫一個 [To-Do List](https://github.com/search?utf8=✓&q=todolist&type=)，就會看到下圖畫面：

![](https://ithelp.ithome.com.tw/upload/images/20171206/20040221KBWy28kNPW.png "https://ithelp.ithome.com.tw/upload/images/20171206/20040221KBWy28kNPW.png")

步驟一：像是你打了 todolist 關鍵字， Repositories 是別人的專案名稱、Code 則是觀看別人的片段程式碼，像我很喜歡看 Code，例如我學會了一個 JavaScript 的 forEach，但想要多找些範例加深自己觀念時，輸入關鍵字就有很多 Code 可以參考。

步驟二 ~ 四：我自己比較習慣用「 Best match \(關鍵字吻合度\) 」、「 Most stars \(星等排序\) 」來下拉尋找，當我在學新技術時，我會反其道而行找星星最少的，因為現在的我剛學會某個程式，想要更進一步瞭解更多，所以我自然要找我的「同學」，或是比我厲害一點的，通常星星多表示他寫的 Code 很漂亮，或整合了許多功能，這樣反而會阻礙我只是想學一個觀念的途徑。除非是說我要找一個熱門的套件，例如網頁動態日曆、燈箱效果時，自然是去找星星最多且有持續在更新的專案會比較 ok。

所以請記得在學程式時，你應該找的學習資源是「比你厲害一點的同學」，而不是大神，當你吸收了同學的養分越變越強，看的 star 越高也都看得懂得時候，恭喜你，你慢慢掌握這技術了。

## 看不懂程式碼，線上影音教學是你的好朋友

有的時候你還是會遇到看了別人部落格，但自己在練習時還是無法做出一樣的功能，有可能是部落格寫錯、少貼一些 Code、環境不一樣等諸多原因，所以我也會習慣用 [YouTube](https://www.youtube.com/) 來下關鍵字，看是否有人有教學錄影。另外[ ](https://www.udemy.com/)[Udemy](https://www.udemy.com/) 也是一個不錯的線上課程平台，主要也以程式課程居多，同時也有許多免費程式課程，優惠期間也長有特價 300 優惠，雖然大部分都是英文課程，但幾乎都有支援字幕，甚至透過 [Google 翻譯軟體即時翻譯](https://softnshare.wordpress.com/2017/07/21/udemysubtitlesandgoogletranslate/)。

這樣好處在於至少照著影片上的講師一起做，或下載他的範例程式碼，也有助於你學習程式上會比較順利，想什麼時候上課就自己安排時間學習。

## 不要尋找過時的文章

技術更新快速，假使你在找解法是三四年前的文章時就要保持懷疑猜測態度，不要盡信，較好的方式可以用 Google 搜尋的下方的功能列。 像是如果你英文不好，也可以先搜尋繁體中文，若還是不行就搜尋「所有中文網頁」，可以進階找到簡體教學，時間區間抓一年以內其實資訊就還蠻新的了。

經由過濾和交叉比對後，找的文章自然也就比較新，或是到目前最大的程式論壇 [StackOverflow](https://stackoverflow.com/) 下關鍵字，找投票贊成數多的文章來觀看也 ok。

![](https://ithelp.ithome.com.tw/upload/images/20171206/20040221mrlYuHlzOU.png "https://ithelp.ithome.com.tw/upload/images/20171206/20040221mrlYuHlzOU.png")

## 簡報網站都會有意想不到的乾貨

我在學新技術的時候，還蠻常會去能夠上傳簡報的服務網站看看的，通常有人整理技術簡報並上傳，往往都是講師級的 Level，簡報品質自然壞不到哪裡去。我自己最常去的則是 [SlideShare](https://www.slideshare.net/) 與 [SpeakerDeck](https://speakerdeck.com/)

## 圖片搜尋

有時候在找靈感時，也會用圖片搜尋的方式，舉例來說我要找一個 [jQuery slider](https://goo.gl/yc9jj6) 的效果，就可以先初步過濾哪些 Slider 做得不錯再點擊觀看文章，像是一些動畫效果的關鍵字，之前我也有整理一份起來，也提供[連結](https://www.facebook.com/hexschool/photos/a.610345345781449.1073741828.608977889251528/671392703010046/?type=3&permPage=1)給各位參考。

## 結尾

希望以上這些方式能夠打通你對 Google 關鍵字的想像搜尋空間，除了單純文字吸收，其實還是有不少可以幫助學習的管道。

--

阿杜：「阿你是 Google 到了沒辣！！」  
我：「還沒啊，你這麼會估你來估啊。」  
阿杜：「我等到要度估了啦怎麼估！！」  
我：「......」
