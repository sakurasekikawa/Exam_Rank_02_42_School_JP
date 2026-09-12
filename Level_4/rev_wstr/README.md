## 課題

```BASH
演習名 : rev_wstr
提出ファイル : rev_wstr.c
使用可能な関数 : write, malloc, free
--------------------------------------------------------------------------------

文字列を1つ引数として受け取り、その単語を逆の順序で表示するプログラムを書いて
ください。

「単語」とは、スペースやタブ、または文字列の先頭・末尾で区切られた文字列の一部分の
ことです。

引数の数が1個でない場合は、プログラムは改行（\n）を表示します。

テストされる引数には「余分な」スペースは含まれません（つまり先頭・末尾にスペースは
なく、単語は常にちょうど1つのスペースで区切られています）。

例:

$> ./rev_wstr "You hate people! But I love gatherings. Isn't it ironic?" | cat -e
ironic? it Isn't gatherings. love I But people! hate You$
$>./rev_wstr "abcdefghijklm"
abcdefghijklm
$> ./rev_wstr "Wingardium Leviosa" | cat -e
Leviosa Wingardium$
$> ./rev_wstr | cat -e
$
$>
```

**オフラインでのコンパイルとテスト**

- **コンパイル:** `gcc -Wall -Wextra -Werror rev_wstr.c -o rev_wstr`
- **例:** `./rev_wstr "You hate people! But I love gatherings. Isn't it ironic?" | cat -e`

補足: コマンドはリポジトリのルートから実行してください。
