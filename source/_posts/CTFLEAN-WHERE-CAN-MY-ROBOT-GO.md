---
title: CTFLEARN | WHERE CAN MY ROBOT GO?
date: 2024-02-02
tags:
  - CTFLEARN
  - CTF
  - forensic
  - web
  - osint
---

# challenge

Where do robots find what pages are on a website?

Hint:

> What does disallow tell a robot?


# solution

The challenge is very easy , even though is took me a while to find it out

the challenge  says about robots.txt so i tried to answer that.
but it was wrong

after some thinking i tried to look in to robots.txt  of https://ctflearn.com/robots.txt 

so i found

```
User-agent: *  
Disallow: /70r3hnanldfspufdsoifnlds.html
```

finally the content of `70r3hnanldfspufdsoifnlds.html` is the flag 

![](https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExcWJlc3dmcDlocm8yZG93MHZhMmkxOThqa2ZwNmUxYjBldmY0NW5xeSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/9xt5eMX6WhOhvfWajw/giphy.gif)


which is `CTFlearn{r0b0ts_4r3_th3_futur3}`

