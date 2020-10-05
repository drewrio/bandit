# bandit

ssh -l bandit1 -p 2220 bandit.labs.overthewire.org

bandit1 PW boJ9jbbUNNfktd78OOpsqOltutMc3MY1
bandit 2 CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9
bandit 3 UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
bandit 4 pIwrPrtPN36QITSp3EQaw936yaFoFgAB
bandit 5 koReBOKuIDDepwhWk7jZC0RTdopnAYKh
bandit 6 DXjZPULLxYr17uwoI01bNLQbtFemEgo7
bandit 7 HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs
bandit 8 cvX2JJa4CFALtqS87jk27qwqGhBM9plV
bandit 9 UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded by several ‘=’ characters.

Commands you may need to solve this level

grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd

bandit9 solved with $ cat data.txt | uniq | strings

bandit 10 truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk

had to scroll up to "=========" to find pasword that was preceeding. must be a faster way to do this?

cat data.txt | uniq | strings | grep ========

This isolate the txt file to: (im not sure how grep works yet)
========== the*2i"4
========== password
Z)========== is
&========== truKLdjsbJ5g7yyJ2X2R0o3a5HQJFu

