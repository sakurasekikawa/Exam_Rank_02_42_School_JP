## 課題

```BASH
演習名 : wdmatch
提出ファイル : wdmatch.c
使用可能な関数 : write
--------------------------------------------------------------------------------

2つの文字列を受け取り、1番目の文字列を2番目の文字列に含まれる文字を使って、2番目
の文字列内での出現順序を守りながら構成できるかどうかを判定するプログラムを書いて
ください。

可能な場合は、その文字列を表示し、最後に \n を出力します。不可能な場合は \n の
みを表示します。

引数の数が2個でない場合は、プログラムは \n を表示します。

例:

$>./wdmatch "faya" "fgvvfdxcacpolhyghbreda" | cat -e
faya$
$>./wdmatch "faya" "fgvvfdxcacpolhyghbred" | cat -e
$
$>./wdmatch "quarante deux" "qfqfsudf arzgsayns tsregfdgs sjytdekuoixq " | cat -e
quarante deux$
$>./wdmatch "error" rrerrrfiiljdfxjyuifrrvcoojh | cat -e
$
$>./wdmatch | cat -e
$
```
