---
title: using Kali to crack the wireless
date: 2016-10-10T04:13:32+00:00
author: panhao
layout: post
categories:
  - CS
format: aside
---
&nbsp;

Tools: VMware Fusion, Kali Linux, rockyou.txt

Steps:

  1. install VM & Kali Linux
  2. get a wireless card for cracking

3. change the wireless card to _monitoring mode_

4.Use airodump-ng tosearch the SSID you want to crack

5.use airdump-ng to capture handshake and store it

6.use aireplay-ng to attack

7.use rockyou.txt to get the password

Finally, the password of CSE_7339 is “security”.

The reason of why this way may not be possible to crack a more complex key is that the more complex the key is(more characters),the more time it will take.

And if the password is not in the password list we used(rockyou.txt), maybe we can’t crack it.