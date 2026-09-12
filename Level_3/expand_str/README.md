## 課題

```BASH
演習名 : expand_str
提出ファイル : expand_str.c
使用可能な関数 : write
--------------------------------------------------------------------------------

文字列を1つ受け取り、各単語の間をちょうど3つのスペースで区切り、先頭と末尾には
スペースやタブを付けずに表示し、最後に改行を1つ出力するプログラムを書いてください。

「単語」とは、スペースやタブ、または文字列の先頭・末尾で区切られた文字列の一部分の
ことです。

引数の数が1個でない場合、または単語が1つもない場合は、改行のみを表示してください。

例:

$> ./expand_str "See? It's easy to print the same thing" | cat -e
See?   It's   easy   to   print   the   same   thing$
$> ./expand_str " this        time it      will     be    more complex  " | cat -e
this   time   it   will   be   more   complex$
$> ./expand_str "No S*** Sherlock..." "nAw S*** ShErLaWQ..." | cat -e
$
$> ./expand_str "" | cat -e
$
$>
```
