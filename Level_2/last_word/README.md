## 課題

```BASH
演習名 : last_word
提出ファイル : last_word.c
使用可能な関数 : write
--------------------------------------------------------------------------------

文字列を1つ受け取り、その最後の単語を表示し、最後に \n を1つ出力するプログラムを
書いてください。

「単語」とは、スペースやタブ、または文字列の先頭・末尾で区切られた文字列の一部分の
ことです。

引数の数が1個でない場合、または単語が1つもない場合は、改行を表示してください。

例:

$> ./last_word "FOR PONY" | cat -e
PONY$
$> ./last_word "this        ...       is sparta, then again, maybe    not" | cat -e
not$
$> ./last_word "   " | cat -e
$
$> ./last_word "a" "b" | cat -e
$
$> ./last_word "  lorem,ipsum  " | cat -e
lorem,ipsum$
$>
```
