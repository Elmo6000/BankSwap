# BankSwap
能透過Email 註冊一個帳戶，模擬銀行的功能(換匯、轉帳、存提款)

# 架構
整體Style參考https://app.uniswap.org/#/swap

兌換的匯率利用PHP Simple HTML DOM Parser 爬取台灣銀行牌告匯率

換匯、存提、轉帳皆透過PHP 存取Mysql

顯示餘額透過ajax POST 給PHP

# 使用方法
將repo 存入xampp/htdocs  (xampp v5.6.40)

打開xampp start Apache and Mysql

在http://127.0.0.1/phpmyadmin/ 建立名為final 的資料表並匯入repo 內的final.sql

在http://127.0.0.1/BankSwap/ 可以看到BankSwap 的介面
![image](https://user-images.githubusercontent.com/88305396/149658269-0224fea5-5e39-4389-ac34-818445ff904a.png)

