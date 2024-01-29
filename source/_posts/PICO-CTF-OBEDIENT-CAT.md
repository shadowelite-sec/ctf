---
title: PICO CTF | OBEDIENT CAT
date: 2024-01-29 16:40:13
tags:
---

its is a very very easy challange <!--more-->  

## STEP 1

Download The flag file to a directory

For now we have no idea what this file is, 
but we can easily identify the file type using the linux command `file`
![file](https://raw.githubusercontent.com/shadowelite-sec/blog/main/assets/pico/g1/file.png)

now we know the file is an ASCII text 

## STEP 2

The 'cat' command in Linux is a versatile tool that can be used to concatenate and display the contents of files on the standard output. there is the detailed manual [man cat](https://man7.org/linux/man-pages/man1/cat.1.html)


previousliy we found the the file is an ASCII text so we can use cat command to display what inside that file

![cat](https://raw.githubusercontent.com/shadowelite-sec/blog/main/assets/pico/g1/cat.png)

this is the flag
