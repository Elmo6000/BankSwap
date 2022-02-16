# 架構
整體CSS參考[Uniswap](https://app.uniswap.org/#/swap)

兌換的匯率利用PHP Simple HTML DOM Parser 爬取台灣銀行牌告匯率

換匯、存提、轉帳皆透過PHP 存取Mysql

顯示餘額透過AJAX post 給PHP

# 使用方法
將repo 存入xampp/htdocs  (xampp v5.6.40)

打開xampp start Apache and Mysql

在[phpMyAdmin](http://127.0.0.1/phpmyadmin/) 建立名為final 的資料庫並匯入repo 內的final.sql

在[BankSwap](http://127.0.0.1/BankSwap/) 應該可以看到如下圖的網頁
![image](https://user-images.githubusercontent.com/88305396/149658269-0224fea5-5e39-4389-ac34-818445ff904a.png)
![image](https://user-images.githubusercontent.com/88305396/152166104-b43091ef-2d51-414b-96fb-ded1c76b007f.png)
![image](https://user-images.githubusercontent.com/88305396/152166139-92afaad1-06b0-492a-b97c-79315c5a8cc1.png)
![image](https://user-images.githubusercontent.com/88305396/152166179-36a56b4b-ebda-48c1-b291-6d75c65fec7b.png)
![image](https://user-images.githubusercontent.com/88305396/152166217-0af79020-c421-45f8-9c85-947f7b89aa7d.png)
