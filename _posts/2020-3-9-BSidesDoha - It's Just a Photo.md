---
layout: post
title: BsidesDoha 2020 - MISC — It's Just a Photo — Writeup
---
![alt text](https://raw.githubusercontent.com/deFr0ggy/deFr0ggy.github.io/master/images/Its-Just-a-Photo/logo.png)

I along with **BeeFaauBee09** participated in BSidesDoha-CTF remotely but didn't make it to the top due to time issues as we have to work and travel a lot. Although we gave it a try and found the challenges to be pretty basic. 

This is going to be the solution of the BSidesDoha - **It's Just a Photo** challenge which can be found in the MISC challenges. 

![alt text](https://raw.githubusercontent.com/deFr0ggy/deFr0ggy.github.io/master/images/Its-Just-a-Photo/main.png)

As the name suggests this challenge has to do something with steganography. This challenge provides us with an image. We opened the image with "eog" and found it to be like this.

![alt text](https://raw.githubusercontent.com/deFr0ggy/deFr0ggy.github.io/master/images/Its-Just-a-Photo/img1.png)

On utilizing the file command we can find that this image is in JPEG format.

![alt text](https://raw.githubusercontent.com/deFr0ggy/deFr0ggy.github.io/master/images/Its-Just-a-Photo/img2.png)

After we had this information we used "strings" utility to look for any worthy string possibly flag but we didn't found the flag. Finally i tried utilizing the **steghide** to extract any possible files if embedded with this JPEG file. We also found that there was no actual password set with the file embedded so it extracted the **secret.txt** file which contained the flag!

![alt text](https://raw.githubusercontent.com/deFr0ggy/deFr0ggy.github.io/master/images/Its-Just-a-Photo/img3.png)

Finally we submitted the flag and got our points! 

***
Follow us on **Twitter**
- @deFr0ggy
- @BeeFaauBee09



