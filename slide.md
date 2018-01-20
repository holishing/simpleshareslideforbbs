# BBS & InterNetNews researsh slide share

<r2.bbs[a t]bbs.ccns.ncku.edu.tw>

---

# Getting Started

![](https://i.imgur.com/ovL6YxG.png)

---

# How I Know?

* Know BBS from `telnet` command

* Know ptt.cc again from Facebook and Google.

---

# Started to Research & Teach

* Learn & Help answer newbie questions on [PttNewhand](https://www.ptt.cc/bbs/PttNewhand/index.html) , [ask](https://www.ptt.cc/bbs/ask/index.html) board

* Try apply Personal Board on [telnet://ptt2.cc](telnet://ptt2.cc)

* Learn How to connect to ptt/ptt2 securely (ssh)

---

# Being a Volunteer

* Help manage small board on ptt.cc

* Pass some tests and be an "Angel" in ptt.cc .

---

# Starting make a BBS

* Try ColaBBS in Virtual Machine
* Started to try learn how to `make` in Linux.
![](https://i.stack.imgur.com/OaUca.png)

---

# Just wiki it!

https://github.com/ptt/pttbbs/wiki

---

# From Ptt to Maple3

* the most wisely used version in BBS in Taiwan:
  * [bbslist](https://github.com/holishing/bbslist)


* https://hackmd.io/s/BkJHevM4f

---

# Internet News Server

* Usenet

* https://people.cs.nctu.edu.tw/~liuyh/course/netadm/slides/12_INN.ppt

---

# Group.NCTU.edu.tw

source code: https://github.com/gslin/group-xfer

首頁
![](https://i.imgur.com/Xh0XLvE.png)

---

使用者條款
![](https://i.imgur.com/IXOlaZE.png)

---

申請帳號
![](https://i.imgur.com/79HPnHu.png)

相關 blog
https://web.archive.org/web/20121104063656/http://group.nctu.edu.tw:80/blog/

---

# Group.NCTU.edu.tw 系統說明
https://web.archive.org/web/20120317233841/http://group.nctu.edu.tw:80/intro/

---

創設目的

在台灣的網路社會中，BBS 的使用相當盛行，看板之間的轉信使得資訊流通的速度加
快。透過 innbbsd 做少數站台 (小於四站) 的轉信是相當方便的，但超過四站之後，僅
使用 innbbsd 互轉會使得設定變得相當冗長。

![](https://i.imgur.com/uE9Gd7Q.png)

（圖一）互轉架構

---

一般來說，大量站台的轉信都會使用 News Server 進行星狀流通，
Group.NCTU.edu.tw 即是為此而成立。

![](https://i.imgur.com/UQcP2MR.png)

（圖二）星狀架構

---

系統架構

以往透過 News Server 轉信會使用同一個 Newsgroup Name，如台灣 386BSD 板的
Newsgroup Name 為 `tw.bbs.comp.386bsd`。

在本系統中，對於同一個看板之間的轉信，我們揚棄此種觀念：也就是說，對於同一
個板的轉信，不同的站是使用不同的 Newsgroup Name。

---

本系統中，Newsgroup Name 固定為 group.[站台名稱].[群組名稱]，其中 [站台名
稱] 的部分使用 twbbs.org 的網域名稱做為判別站台的方式，譬如 ptt、zoo 等等...。
[群組名稱] 則是使用者自己選擇，可以使用 3 ~ 64 個字元 (小寫英文字母、數字、底
線)。

---

使用規定

使用規定的部分，請參考申請時的使用規章。
使用方法 (BBS 轉信管理者部分)

請您先參考上方所描述的系統架構，請您申請 twbbs.org 的 Domain Name。申請以
後，若使用者有設定您可以轉他的 Newsgroup，則 Newsgroup Name 為 `group.[您的
twbbs.org 名稱].[使用者的群組名稱]`。

---

舉例來說，Ptt.twbbs.org 如果要轉 testboard 這個板，那麼他所要轉的
Groupname 則是：

`group.ptt.testboard`

轉信的 News Server 為 group.nctu.edu.tw，二十四小時內的抓取次數請維持在
144 次以下。

---

使用方法 (使用者部分)

Under Construction.

如果有任何問題，您可以寫信到 usenet@group.nctu.edu.tw 詢問，或於
tw.bbs.netnews 討論。

---

# To be continued...
