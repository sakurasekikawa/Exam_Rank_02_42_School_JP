## 課題

```BASH
演習名 : rostring
提出ファイル : rostring.c
使用可能な関数 : write, malloc, free
--------------------------------------------------------------------------------

文字列を1つ受け取り、単語を1つ左に回転させたあとの文字列を表示するプログラムを
書いてください。

つまり、最初の単語が最後になり、他の単語はその順序を保ちます。

「単語」とは、スペースやタブ、または文字列の先頭・末尾で区切られた文字列の一部分の
ことです。

出力では単語をちょうど1つのスペースで区切ってください。

引数が1個未満の場合は、プログラムは改行（\n）を表示します。

例:

$>./rostring "abc   " | cat -e
abc$
$>
$>./rostring "Que la      lumiere soit et la lumiere fut"
la lumiere soit et la lumiere fut Que
$>
$>./rostring "     AkjhZ zLKIJz , 23y"
zLKIJz , 23y AkjhZ
$>
$>./rostring "first" "2" "11000000"
first
$>
$>./rostring | cat -e
$>
```

**オフラインでのコンパイルとテスト**

- **コンパイル:** `gcc -Wall -Wextra -Werror rostring.c -o rostring`
- **例:** `./rostring "Que la      lumiere soit et la lumiere fut"`

補足: コマンドはリポジトリのルートから実行してください。
