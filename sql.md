# cve
# Easy Blog Site has sql injection in the login.php file

## supplier

https://code-projects.org/easy-blog-site-in-php-with-source-code

## Vulnerability file

login.php

## describe

This code queries whether the current account exists from the database, and the username and password are not filtered in any way, nor are they normalized through function conversion, resulting in any password being able to log in to the account.

![image-20260323200248373](cve/image-20260323200248373.png)

## POC

![image-20260323201149559](cve/image-20260323201149559.png)

![image-20260323201209277](cve/image-20260323201209277.png)

![image-20260323201323539](cve/image-20260323201323539.png)

## Result

![image-20260323201209277](cve/image-20260323201209277.png)

登录其他账户
