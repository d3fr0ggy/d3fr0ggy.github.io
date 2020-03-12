---
layout: post
title: BsidesDoha 2020 - Reverse Engineering — RE 101 — Writeup
---
![alt text](https://raw.githubusercontent.com/deFr0ggy/deFr0ggy.github.io/master/images/Its-Just-a-Photo/logo.png)

There was only one challenge in the Reverse Engineering Category. As it had the 30 points we were pretty sure that this challenge is going to be an easy one. 

![alt text](https://raw.githubusercontent.com/deFr0ggy/deFr0ggy.github.io/master/images/RE-101/img1.png)

A binary executable was provided with this challenge. On downloading it in Kali Linux and running the **file** command we can see that this is an **ELF Executable**.

![alt text](https://raw.githubusercontent.com/deFr0ggy/deFr0ggy.github.io/master/images/RE-101/img2.png)

From here onwards we moved onto utilzing the **strings** utility and found our flag with some garbage! 

![alt text](https://raw.githubusercontent.com/deFr0ggy/deFr0ggy.github.io/master/images/RE-101/img3.png)

On removing the garbage we had our exact flag which was required to be submitted! 

### Other Ways

There are also multiple ways of doing this. 

- Opening the file in the text editor and grabbing the flag! 
- Opening the file with IDA Community/Pro and grabbing the flag!
- Opening the file in Ghidra and grabbing the flag! 

As we found the flag while looking for low hanging fruits so we actually didn't had to move onto trying other tools. 

***
Follow us on **Twitter**
- @deFr0ggy
- @BeeFaauBee09
