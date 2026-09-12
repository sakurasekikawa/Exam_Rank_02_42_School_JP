## 課題

```BASH
演習名 : repeat_alpha
提出ファイル : repeat_alpha.c
使用可能な関数 : write
--------------------------------------------------------------------------------

repeat_alpha という名前のプログラムを書いてください。このプログラムは文字列を1つ
受け取り、アルファベットの各文字をそのアルファベット順の番号の回数だけ繰り返して
表示し、最後に改行を1つ出力します。

'a' は 'a' に、'b' は 'bb' に、'e' は 'eeeee' になります…等。

大文字・小文字は変更しません。

引数の数が1個でない場合は、改行のみを表示してください。

例:

$>./repeat_alpha "abc"
abbccc
$>./repeat_alpha "Alex." | cat -e
Alllllllllllleeeeexxxxxxxxxxxxxxxxxxxxxxxx.$
$>./repeat_alpha 'abacadaba 42!' | cat -e
abbacccaddddabba 42!$
$>./repeat_alpha | cat -e
$
$>
$>./repeat_alpha "" | cat -e
$
$>
```
