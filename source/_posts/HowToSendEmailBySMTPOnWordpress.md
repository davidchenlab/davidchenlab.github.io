---
title: 如何在 WORDPRESS 中設定 SMTP 發信？WP MAIL SMTP BY WPFORMS
categories:
  - WordPress
tags:
  - WordPress
  - Website
  - SMTP
abbrlink: 3141599f
date: 2021-10-26 12:24:36
---
### 如何在 WORDPRESS 中設定 SMTP 發信？WP MAIL SMTP BY WPFORMS
<!--more-->
這篇介紹如何在 WORDPRESS 中設定 SMTP 發信？WP MAIL SMTP BY WPFORMS。

### How to use
```sh
1.在 WordPress 搜尋並安裝 WP Mail SMTP by WPForms 。

2.設定

寄件者電子郵件地址: 自己的Gmail

郵件程式 : 其它SMTP

SMTP 伺服器：smtp.gmail.com
加密方式：TLS  (使用安全性憑證加密)
SMTP 通訊埠： 587

3.發送測試郵件一開始會收不到是因為要啟用低安全性應用程式的存取權限

4.若收到mailer-daemon@googlemail.com寄來的系統找不到 aaa 這個網域，因此未將你的郵件傳送到 bbb。請檢查該網域是否正確無誤或有不必要的空格，然後再試一次。

修改設定:在WPForms -> all Forms -> Simple Contact Form -> Edit -> Settings -> Notifications -> Send To Email Address 設定成 {admin_email}
```