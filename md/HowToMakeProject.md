```
注意事項：
	1. 純屬個人經驗分享
	2. 本篇內容以開發 Java 為主，其他語言則需依照語言的狀況去做調整
```

## 目錄

[TOC]

## 前言

一名工程師在工作上除了既有專案的維運，在一些時候是會開發新的專案，這專案可能是自己想開發也可能是工作上的需求。這樣零零總總下來，一個工程師會有數個專案同時在進行。除此之外，再考慮到不同的專案，可能有不同的人一起進行開發，這時候的情況就會更為複雜。因此，在接手一個專案時如何進行有效的開發管理就變得極為重要。

## 開發專案需要什麼？

簡單的條列大概至少需要的內容，如下：

1. 一種以上的程式語言
2. 一名以上的工程師
3. 一人以上的團隊
4. 一個以上的專案（一個專案可能是由許多小專案所組成）
5. 一種以上的套件函式庫（這邊舉 Java來說就是很多的 jar）

## 根據以上需要些什麼？

1. 撰寫 Document（簡單來說是程式文件化）
>
一套程式的生命週期長可數十年短則數天甚至數小時，而一名工程師平均在職也僅僅 2年左右，程式的交接是必然發生的情形，而程式文件化的優劣將決定接手者的痛苦指數。回到重點，一個可以輕鬆撰寫文件的方法將可以讓工程師有更良好的習慣

2. 撰寫 開發日誌
>
開發日誌與 Document 都是可以交接的內容，同時還是可以有效記錄自己職涯過程。在許多時候如：轉職、進修... 等。這份日誌將會為自己帶來許多的好處，而在平時也會為自己及專案管理人帶來明確的訊息。

3. 團隊溝通及開發的工具
>
這是一種現在很常見的工具，以最近來看有很紅的 Slack 還有淺顯易懂的 Trello 以及功能極為多的 Redmine 都是非常不錯的，為自己的團隊選擇一個有效的工具，可以達到哪怕人在千里之外也能共同進行專案開發。

4. 專案版本管控工具（必要）
>
專案的開發永遠不是一條直線，哪怕一個人開發都可能會同時有多種需求。常見的專案版本控管工具如：Git、SVN、CVS... 等。可以說在進行專案開發時這是絕對必要的，否則很可能會寸步難行或專案死亡。

5. 語言套件管理工具（必要）
>
這邊以 Java為例在物件導向概念中，產生了很多現成的套件，通過這些套件我們可以輕鬆的去使用一些複雜的功能，例如：網路傳輸、NIO、資料轉換... 等。這邊我們來講講沒有套件管理工具，會發生什麼事情。一般常見的有版本衝突、版本不一致、上下不相容... 等。最嚴重會造成專案死亡及專案無法控制。所以選擇一套穩定強大的套件管理工具就很重要拉，現在常見的 Java套件管理工具，如：Apache Maven, Gradle, Ant... 等。

P.S. 目前小編在 撰寫 Document 及 開發日誌 都是利用 markdown 語法進行，這是一個可以用簡單語法撰寫出網頁及文件的語言，同時非常適合利用 Git 進行版本控管。最後，此網頁內容也是使用 markdown 語法所撰寫後輸出。

## 總結

工具其實是一直推成出新沒有絕對的最好，只要合適都是最棒的工具。在現在的工作中版本控管幾乎是必要的條件門檻之一，如果您未來期望踏入軟體工程領域，那版本控管請務必多多學習。

