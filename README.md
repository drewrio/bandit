# bandit passwords

ssh -l bandit11 -p 2220 bandit.labs.overthewire.org

bandit 1 boJ9jbbUNNfktd78OOpsqOltutMc3MY1

bandit 2 CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

bandit 3 UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK

bandit 4 pIwrPrtPN36QITSp3EQaw936yaFoFgAB

bandit 5 koReBOKuIDDepwhWk7jZC0RTdopnAYKh

bandit 6 DXjZPULLxYr17uwoI01bNLQbtFemEgo7

bandit 7 HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs

bandit 8 cvX2JJa4CFALtqS87jk27qwqGhBM9plV

bandit 9 UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR

bandit 10 truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk

bandit 11 IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR

bandit 12 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu


Level Goal

The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions


Commands you may need to solve this level

grep, sort, uniq, strings, base64, tr, tar, gzip, bzip2, xxd


Helpful Reading Material

https://en.wikipedia.org/wiki/Rot13

cat data.txt

Gur cnffjbeq vf 5Gr8L4qetPEsPk8htqjhRK8XSP6x2RHh

$ echo "Gur cnffjbeq vf 5Gr8L4qetPEsPk8htqjhRK8XSP6x2RHh" | tr ‘n-za-mN-ZA-M’ ‘a-zA-Z’

The password is 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu

alternitive is 
$ cat data.txt echo | tr ‘n-za-mN-ZA-M’ ‘a-zA-Z'

echo data.txt | tr ‘n-za-mN-ZA-M’ ‘a-zA-Z'

cat: echo: No such file or directory

The password is 5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu

