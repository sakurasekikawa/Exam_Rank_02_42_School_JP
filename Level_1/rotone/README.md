## 課題

```BASH
演習名 : rotone
提出ファイル : rotone.c
使用可能な関数 : write
--------------------------------------------------------------------------------

文字列を1つ受け取り、各文字をアルファベット順で次の文字に置き換えて表示する
プログラムを書いてください。

'z' は 'a' に、'Z' は 'A' になります。大文字・小文字は変更しません。

出力の最後には \n を1つ出力します。

引数の数が1個でない場合は、プログラムは \n を表示します。

例:

$>./rotone "abc"
bcd
$>./rotone "Les stagiaires du staff ne sentent pas toujours tres bon." | cat -e
Mft tubhjbjsft ev tubgg of tfoufou qbt upvkpvst usft cpo.$
$>./rotone "AkjhZ zLKIJz , 23y " | cat -e
BlkiA aMLJKa , 23z $
$>./rotone | cat -e
$
$>
$>./rotone "" | cat -e
$
$>
```
