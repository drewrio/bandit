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
bandit 10 IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

The password for the next level is stored in the file data.txt, which contains base64 encoded data

Commands you may need to solve this level

grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd

https://en.wikipedia.org/wiki/Base64

$ cat | base64 -d data.txt
The password is IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

base64 enocding use -d to decode

