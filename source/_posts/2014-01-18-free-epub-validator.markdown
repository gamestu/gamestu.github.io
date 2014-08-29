---
layout: post
title: "免費好用的EPUB Validator - pagina EPUB-Checker"
date: 2014-01-18 16:17:24 +0800
comments: true
categories: 數位出版
---

從EPUB2時代開始，我就一直說讓EPUB能夠通過驗證很重要。現在是更重要了，因為沒有通過驗證的話，是沒辦法將EPUB送到iBookstore或Google上架的。

EPUB2時代，使用Sigil就有內建idpf提供的Validator，按一下就好了，非常方便。但在EPUB3的時代，Sigil就不是個可用的工具，所以如果有一個單純的工具專門做驗證就好了。

<!-- more -->

於是我找到這個工具，[pagina EPUB-Checker][1]，免費，穩定，跨平台（提供Mac/Linux/Windows版本）。使用上也非常方便，把做好的EPUB檔拉近程式的框框中就好了。

當然目標是「不要做出不能通過validator」的EPUB檔，但以目前的情況來看，有許多軟體本身就還達不到這個標準，而且有時候不得不處理「別人不知道用什麼工具做出來的EPUB檔」，所以一個不依賴任何軟體的validator仍是一個必需的工具，它能夠幫你將問題單純化，任何奇怪的檔案到你手上都可以診斷出問題所在。

其他Validator：

1. [IDPF EPUB Validator][2]：算是正宗的，可以從這裡載到validator的原始碼。此外也提供網頁介面供人使用。但限制是有10mb的限制，圖比較多的檔案就會超過。此外，如果是商業使用的檔案，建議不要使用。
2. [台灣數位出版聯盟提供的Validator服務][3]：跟IDPF提供的一樣，有將錯誤訊息做了中文化，如果看不懂英文可以使用。一樣是web服務，所以建議商業檔案還是儘量不要用吧。
3. [ePub Checker][4]：是個付費Mac App，原本是打算使用這款，但是Mac升級到Maverick之後就掛掉了Orz。後來發現pagina EPUB-Checker可以完全取代它的功能（還免費），就跟他說掰掰了。


[1]:    http://www.pagina-online.de/produkte/epub-checker/ "pagina EPUB-Checker"
[2]:    http://validator.idpf.org/ "IDPF EPUB Validator"
[3]:    http://validator.cloudapp.net/
[4]:    https://itunes.apple.com/au/app/epub-checker/id453480324?mt=12