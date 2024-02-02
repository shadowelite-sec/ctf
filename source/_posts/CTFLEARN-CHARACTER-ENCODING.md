---
title: CTFLEARN | CHARACTER ENCODING
date: 2024-02-01
tags:
  - CTFLEARN
  - crypto
  - CTF
---
# challenge

https://ctflearn.com/challenge/115

`41 42 43 54 46 7B 34 35 43 31 31 5F 31 35 5F 55 35 33 46 55 4C 7D`

decode the given cipher


# solution
its very easy to identify that its hex encoded

so i use cyberchef to decode 

add recipe `from hex`

![](CTFLEARN-CHARACTER-ENCODING/image-20240201105626812.png)

add we got the flag : `ABCTF{45C11_15_U53FUL}`

![](CTFLEARN-CHARACTER-ENCODING/image-20240201105754140.png)
