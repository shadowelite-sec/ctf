---
title: PICO CTF | PYTHON WRANGLING
date: 2024-01-29 16:42:45
tags:
---
## Cracking challange

Download All three Files Provided in the challange and copy into one directory

to run a python script `python <file>.py`

here 
```
$ python python ende.py --help

Usage: ende.py (-e/-d) [file]
Examples:
  To decrypt a file named 'pole.txt', do: '$ python ende.py -d pole.txt'

```
according to the script help page we need to pass `flag.txt.en` as an argument

```bash
$ python ende.py -d flag.txt.en

Please enter the password:

```
Now It's Prompting me to Enter a password ,we can find the password just by `cat` command to `pw.txt`

```bash
$ cat pw.txt
6008014f6008014f6008014f6008014f
```
Now we all set just paste the password like This

```bash
$ python ende.py -d flag.txt.en

Please enter the password:6008014f6008014f6008014f6008014f
picoCTF{4p0110_1n_7h3_h0us3_6008014f}
```
and we got the flag
