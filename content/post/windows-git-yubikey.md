---
title: "Windows Git Yubikey"
date: 2022-01-14T20:00:02+01:00
draft: false
---

I prefer to use git via ssh. And I like to store my ssh private key on a yubikey. 
Using linux, this setup is trivial, just follow the direction from the linked manuals from [yubico](https://developers.yubico.com/PGP/SSH_authentication/)

*But what about my windows client?*

Well, follow the guide for windows [yubico's windows guide](https://developers.yubico.com/PGP/SSH_authentication/Windows.html) and dont forget use the **putty plink** option during the git installation. I dit forget to set it and it took embarassingly long to find that error. 

