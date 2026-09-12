## 課題

```BASH
演習名 : first_word
提出ファイル : first_word.c
使用可能な関数 : write
--------------------------------------------------------------------------------

文字列を1つ受け取り、その最初の単語を表示し、最後に改行を1つ出力するプログラムを
書いてください。

「単語」とは、スペースやタブ、または文字列の先頭・末尾で区切られた文字列の一部分の
ことです。

引数の数が1個でない場合、または単語が1つもない場合は、改行のみを表示してください。

例:

$> ./first_word "FOR PONY" | cat -e
FOR$
$> ./first_word "this        ...    is sparta, then again, maybe    not" | cat -e
this$
$> ./first_word "   " | cat -e
$
$> ./first_word "a" "b" | cat -e
$
$> ./first_word "  lorem,ipsum  " | cat -e
lorem,ipsum$
$>
```
