# Comb

請實作排列組合，如給定abc，則輸出: abc, acb, bac, bca, cab, cba。
這邊只要實作swap函數就好了，輸入輸出規則可以不用管。有興趣的可以看中間遞迴產生排列的程式，之後教授可能會提到。

### input
輸入一字元type和數字N，表示有N個type組成的陣列，例如type為char的話，以abcd...依序呈現，再者如果N=5，則給定abcde。

### output
輸出以遞迴產生的排列組合。每一行為其中一組合，不用特別排序。

input
```
c 4

```

output
```
abcd
abdc
acbd
acdb
adcb
adbc
bacd
badc
bcad
bcda
bdca
bdac
cbad
cbda
cabd
cadb
cdab
cdba
dbca
dbac
dcba
dcab
dacb
dabc

```


