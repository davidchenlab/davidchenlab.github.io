---
title: 虛擬主機+WORDPRESS.ORG+FREENOM.COM+CLOUDFARE=架設網站
categories:
  - Website
tags:
  - Website
  - WordPress
  - Freenom
  - Cloudfare
abbrlink: 3661c38e
date: 2021-10-24 19:30:56
---
### 虛擬主機+WORDPRESS.ORG+FREENOM.COM+CLOUDFARE=架設網站
<!--more-->
這篇介紹虛擬主機+WORDPRESS.ORG+FREENOM.COM+CLOUDFARE=架設網站。

### Step by step
```sh
1.申請Gamil

2.申請000webhost虛擬主機(000webhost.com) -> 用第一步申請的Gamil登入 -> 下一步時安裝WordPress.org


3.WordPress.org安裝完成後 -> 可登入WordPress.org後台({user}.000webhostapp.com/wp-login.php)


4.外觀->佈景主題->搜尋並安裝OceanWP->啟用


5.開始建立屬於自己的網站內容


6.freenom.com申請網域 -> 先檢查欲申請domain是否用過 -> 5個免費的doamin(一年效期) -> 用第一步申請的Gamil登入進行設定


7.Services -> My Domains -> Manange Domain -> Management Tools -> Nameservers -> 點選Use custom nameservers (enter below)


8.將NS01.000WEBHOST.COM NS02.000WEBHOST.COM分別填入Nameserver 1 & 2 -> CHANGE NAMESERVERS


9.000webhost後台 -> Tools -> Set Web Address -> Add Domain -> 填入剛申請的freenom.com Domain -> Park Domain

10.若開啟Domain出現 -> DNS_PROBE_FINISHED_NXDOMAIN -> cmd -> ipconfig/release 、 ipconfig/flushdns 、 ipconfig/renew


11.回到WordPress.org後台 -> 設定 -> 一般 -> WordPress 位址 (網址) 和 網站位址 (網址) -> 填入 https://{domain}


12.HTTP to HTTPS -> 在 https://dash.cloudflare.com/sign-up 用第一步申請的Gamil註冊並登入


13.點選右上角 Add site -> 將domain填入並點選Add site -> 若出現不是已註冊的網域時 -> 回freenom.com將設定改回Use default nameservers (Freenom Nameservers)


14.Add Cloudflare’s nameservers -> 將兩個Cloudflare提供的NameServers填入 Use custom nameservers (enter below) 的 Nameserver 1 & 2


15.三個設定 Automatic HTTPS Rewrites (ON) -> Always Use HTTPS (ON) -> Auto Minify (都打勾) -> Brotli(ON) -> Finish
```