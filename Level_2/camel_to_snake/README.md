## 課題

```BASH
演習名 : camel_to_snake
提出ファイル : camel_to_snake.c
使用可能な関数 : malloc, realloc, write
--------------------------------------------------------------------------------

lowerCamelCase形式の文字列を1つ受け取り、それをsnake_case形式の文字列に変換する
プログラムを書いてください。

lowerCamelCase文字列とは、最初の単語以外の各単語が大文字で始まる文字列のことです。

snake_case文字列とは、各単語がすべて小文字で、アンダースコア "_" で区切られている
文字列のことです。

例:

$>./camel_to_snake "hereIsACamelCaseWord"
here_is_a_camel_case_word
$>./camel_to_snake "helloWorld" | cat -e
hello_world$
$>./camel_to_snake | cat -e
$
```
