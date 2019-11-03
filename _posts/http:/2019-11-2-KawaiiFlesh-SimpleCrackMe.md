---
layout: post
title: Simple crackme — Kawaii Flesh — Writeup
---
![_config.yml]({{ site.baseurl }}images/Kawaii-Flesh-CrackMe/1.png)

This is an easy challenge. All we need is to find the key and the easter egg. Download this file as it is ELF executable i will be using Linux and an amazing utility which will help us in solving this crackme.
On trying to run the program with ltrace utility we can clearly see the MD5 to which the user input is being compared to.

![_config.yml]({{ site.baseurl }}images/Kawaii-Flesh-CrackMe/2.png)

bd4c217637bc828982c090b2de41b84d

![_config.yml]({{ site.baseurl }}images/Kawaii-Flesh-CrackMe/3.png)

On trying to decrypt this hash on Md5 Decryptor website. We are provided with the password.

![_config.yml]({{ site.baseurl }}images/Kawaii-Flesh-CrackMe/4.png)

That’s all! We are done with this crackme!
