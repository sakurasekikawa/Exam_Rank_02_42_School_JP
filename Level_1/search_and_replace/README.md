## 課題

```BASH
演習名 : search_and_replace
提出ファイル : search_and_replace.c
使用可能な関数 : write, exit
--------------------------------------------------------------------------------

search_and_replace という名前のプログラムを書いてください。このプログラムは3つの
引数を受け取ります。1番目の引数は文字列で、その中の文字（2番目の引数）を別の文字
（3番目の引数）に置き換えます。

引数の数が3個でない場合は、改行のみを表示してください。

2番目の引数が1番目の文字列に含まれていない場合は、プログラムはその文字列をそのまま
出力し、最後に改行を1つ出力します。

例:

$>./search_and_replace "Papache est un sabre" "a" "o"
Popoche est un sobre
$>./search_and_replace "zaz" "art" "zul" | cat -e
$
$>./search_and_replace "zaz" "r" "u" | cat -e
zaz$
$>./search_and_replace "jacob" "a" "b" "c" "e" | cat -e
$
$>./search_and_replace "ZoZ eT Dovid oiME le METol." "o" "a" | cat -e
ZaZ eT David aiME le METal.$
$>./search_and_replace "wNcOre Un ExEmPle Pas Facilw a Ecrirw " "w" "e" | cat -e
eNcOre Un ExEmPle Pas Facile a Ecrire $
```
