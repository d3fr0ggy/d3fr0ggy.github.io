---
layout: post
title: BsidesDoha 2020 - Forensics — If You Like It, Put Encryption on It — Writeup
---

![alt text](https://raw.githubusercontent.com/deFr0ggy/deFr0ggy.github.io/master/images/Its-Just-a-Photo/logo.png)

This challenge is the first in the Forensics category and as the name suggests the challenge has to do something with encryption as well.

![alt text](https://raw.githubusercontent.com/deFr0ggy/deFr0ggy.github.io/master/images/Encryption1/img1.png)

In this challenge we are provided with a ZIP file. On downloading and trying to unzip the file we can see that the ZIP is password protected and it does includes the flag file.

![alt text](https://raw.githubusercontent.com/deFr0ggy/deFr0ggy.github.io/master/images/Encryption1/img2.png)

As we don't know the password. What i did here was to try **zip2john** which showed the salted hash.

![alt text](https://raw.githubusercontent.com/deFr0ggy/deFr0ggy.github.io/master/images/Encryption1/img3.png)

From here, we saved the salted hash to **Hash.txt** file. 

![alt text](https://raw.githubusercontent.com/deFr0ggy/deFr0ggy.github.io/master/images/Encryption1/img4.png)

From here onwards we need to crack the password. **John** being famous and easy to use we tried it and it provided us the password for the ZIP file. **John** cracked the password which we utilized the unzip the ZIPPED folder and retrieved our flag!

![alt text](https://raw.githubusercontent.com/deFr0ggy/deFr0ggy.github.io/master/images/Encryption1/img5.png)

***
Follow us on **Twitter**
- @deFr0ggy
- @BeeFaauBee09
