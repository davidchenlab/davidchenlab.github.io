---
title: How To Solve Ftp_Put() CanNot Open That File NoSuch File Or Directory
categories:
  - WordPress
tags:
  - WordPress
  - Website
  - FTP
  - 000webhost
abbrlink: f29c18d3
date: 2021-10-28 15:08:04
---
### How To Solve Ftp_Put() CanNot Open That File NoSuch File Or Directory
<!--more-->
這篇介紹How To Solve Ftp_Put() CanNot Open That File NoSuch File Or Directory。

### Reason & Solution
```sh
Reason:用FTP上傳目錄至WordPress的Plugin，上傳到一半會出現Ftp_put(): Can’t Open That File: No Such File Or Directory.

原因是000webhost的Dashboard中的Inode Usage Quota用到100%.

解決方法:刪除用不到的Plugin、佈景主題以及文章…來降低數量
```
