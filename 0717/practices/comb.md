# Comb

請實作排列組合，如給定abc，則輸出：`abc, acb, bac, bca, cab, cba`。
這邊只要實作 swap 函數就好了，輸入輸出規則可以不用管。有興趣的可以看中間遞迴產生排列的程式，之後教授可能會提到。

## 輸入

輸入一字元 type 和數字 $N$，表示有 $N$ 個 type 組成的陣列，例如 type 為 `char` 的話，以 `abcd...` 依序呈現，再者如果 $N=5$，則給定 `abcde`。

## 輸出

輸出以遞迴產生的排列組合。每一行為其中一組合，不用特別排序。

### Example Input

```plain
c 4

```

### Output

```plain
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
