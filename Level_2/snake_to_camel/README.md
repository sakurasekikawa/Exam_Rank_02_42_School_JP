## 課題

```BASH
演習名 : snake_to_camel
提出ファイル : snake_to_camel.c
使用可能な関数 : malloc, free, realloc, write
--------------------------------------------------------------------------------

snake_case形式の文字列を1つ受け取り、それをlowerCamelCase形式の文字列に変換する
プログラムを書いてください。

snake_case文字列とは、各単語がすべて小文字で、アンダースコア "_" で区切られている
文字列のことです。

lowerCamelCase文字列とは、最初の単語以外の各単語が大文字で始まる文字列のことです。

例:

$>./snake_to_camel "here_is_a_snake_case_word"
hereIsASnakeCaseWord
$>./snake_to_camel "hello_world" | cat -e
helloWorld$
$>./snake_to_camel | cat -e
$
```
