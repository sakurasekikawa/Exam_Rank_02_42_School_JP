## 課題

```BASH
演習名 : ulstr
提出ファイル : ulstr.c
使用可能な関数 : write
--------------------------------------------------------------------------------

文字列を1つ受け取り、すべての文字の大文字・小文字を反転するプログラムを書いて
ください。それ以外の文字はそのままにします。

結果を表示し、最後に '\n' を1つ出力してください。

引数の数が1個でない場合は、プログラムは '\n' を表示します。

例:

$>./ulstr "L'eSPrit nE peUt plUs pRogResSer s'Il staGne et sI peRsIsTent VAnIte et auto-justification." | cat -e
l'EspRIT Ne PEuT PLuS PrOGrESsER S'iL STAgNE ET Si PErSiStENT vaNiTE ET AUTO-JUSTIFICATION.$
$>./ulstr "S'enTOuRer dE sECreT eSt uN sIGnE De mAnQuE De coNNaiSSanCe.  " | cat -e
s'ENtoUrER De SecREt EsT Un SigNe dE MaNqUe dE COnnAIssANcE.  $
$>./ulstr "3:21 Ba  tOut  moUn ki Ka di KE m'en Ka fe fot" | cat -e
3:21 bA  ToUT  MOuN KI kA DI ke M'EN kA FE FOT$
$>./ulstr | cat -e
$
```
