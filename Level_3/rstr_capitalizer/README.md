## 課題

```BASH
演習名 : rstr_capitalizer
提出ファイル : rstr_capitalizer.c
使用可能な関数 : write
--------------------------------------------------------------------------------

1つ以上の文字列を受け取り、それぞれの引数について、各単語の最後の文字（アルファ
ベット）を大文字にし、残りを小文字にして、その結果を表示し、最後に \n を1つ出力
するプログラムを書いてください。

「単語」とは、スペースやタブ、または文字列の先頭・末尾で区切られた文字列の一部分の
ことです。単語が1文字だけの場合は、その文字を大文字にしてください。

「アルファベット」とは、[a-zA-Z] に含まれる文字のことです。

引数がない場合は、\n を表示してください。

例:

$> ./rstr_capitalizer | cat -e
$
$> ./rstr_capitalizer "a FiRSt LiTTlE TESt" | cat -e
A firsT littlE tesT$
$> ./rstr_capitalizer "SecONd teST A LITtle BiT   Moar comPLEX" "   But... This iS not THAT COMPLEX" "     Okay, this is the last 1239809147801 but not    the least    t" | cat -e
seconD tesT A littlE biT   moaR compleX$
   but... thiS iS noT thaT compleX$
     okay, thiS iS thE lasT 1239809147801 buT noT    thE leasT    T$
$>
```
