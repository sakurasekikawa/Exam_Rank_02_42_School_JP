## 課題

```BASH
演習名 : str_capitalizer
提出ファイル : str_capitalizer.c
使用可能な関数 : write
--------------------------------------------------------------------------------

1つ以上の引数（文字列）を受け取り、それぞれの引数について、各単語の最初の文字
（アルファベットである場合）を大文字にし、残りを小文字にして、標準出力に結果を
表示し、最後に \n を1つ出力するプログラムを書いてください。

「単語」とは、スペースやタブ、または文字列の先頭・末尾で区切られた文字列の一部分の
ことです。単語が1文字だけの場合は、その文字を大文字にしてください。

引数がない場合は、プログラムは \n のみを表示してください。

例:

$> ./str_capitalizer | cat -e
$
$> ./str_capitalizer "a FiRSt LiTTlE TESt" | cat -e
A First Little Test$
$> ./str_capitalizer "__SecONd teST A LITtle BiT   Moar comPLEX" "   But... This iS not THAT COMPLEX" "     Okay, this is the last 1239809147801 but not    the least    t" | cat -e
__second Test A Little Bit   Moar Complex$
   But... This Is Not That Complex$
     Okay, This Is The Last 1239809147801 But Not    The Least    T$
$>
```

**オフラインでのコンパイルとテスト**

- **コンパイル:** `gcc -Wall -Wextra -Werror str_capitalizer.c -o str_capitalizer`
- **例:** `./str_capitalizer "a FiRSt LiTTlE TESt" | cat -e`

補足: コマンドはリポジトリのルートから実行してください。
