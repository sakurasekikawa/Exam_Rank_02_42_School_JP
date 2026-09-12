## 課題

```BASH
演習名 : epur_str
提出ファイル : epur_str.c
使用可能な関数 : write
--------------------------------------------------------------------------------

文字列を1つ受け取り、単語の間をちょうど1つのスペースで区切り、先頭と末尾には
スペースやタブを付けずに表示し、最後に \n を1つ出力するプログラムを書いてください。

「単語」とは、スペースやタブ、または文字列の先頭・末尾で区切られた文字列の一部分の
ことです。

引数の数が1個でない場合、または表示すべき単語がない場合は、プログラムは \n を
表示します。

例:

$> ./epur_str "See? It's easy to print the same thing" | cat -e
See? It's easy to print the same thing$
$> ./epur_str " this        time it      will     be    more complex  . " | cat -e
this time it will be more complex .$
$> ./epur_str "No S*** Sherlock..." "nAw S*** ShErLaWQ..." | cat -e
$
$> ./epur_str "" | cat -e
$
$>
```
