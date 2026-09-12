## 課題

```BASH
演習名 : union
提出ファイル : union.c
使用可能な関数 : write
--------------------------------------------------------------------------------

2つの文字列を受け取り、いずれかの文字列に現れる文字を重複なく表示するプログラムを
書いてください。

表示順序はコマンドライン上で文字が現れる順とし、最後に \n を1つ出力します。

引数の数が2個でない場合は、プログラムは \n を表示します。

例:

$>./union zpadinton "paqefwtdjetyiytjneytjoeyjnejeyj" | cat -e
zpadintoqefwjy$
$>./union ddf6vewg64f gtwthgdwthdwfteewhrtag6h4ffdhsd | cat -e
df6vewg4thras$
$>./union "rien" "cette phrase ne cache rien" | cat -e
rienct phas$
$>./union | cat -e
$
$>
$>./union "rien" | cat -e
$
$>
```
