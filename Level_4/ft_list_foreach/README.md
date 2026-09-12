## 課題

```BASH
演習名 : ft_list_foreach
提出ファイル : ft_list_foreach.c, ft_list.h
使用可能な関数 : 
--------------------------------------------------------------------------------

連結リストと関数ポインタを受け取り、その関数をリストの各要素に適用する関数を
書いてください。

関数は次のように宣言してください：

void    ft_list_foreach(t_list *begin_list, void (*f)(void *));

`f` が指す関数は次のように使用されます：

(*f)(list_ptr->data);

次の構造体を使用し、`ft_list.h` という名前のファイルとして提出してください：

typedef struct    s_list
{
    struct s_list *next;
    void          *data;
}                 t_list;
```

**オフラインでのコンパイルとテスト**

- **コンパイル:** `gcc -Wall -Wextra -Werror ft_list_foreach.c -o ft_list_foreach`（テストファイルが提供されている場合は、そのテストと一緒にコンパイルしてください）
- **例:** `ft_list.h` をインクルードし `ft_list_foreach` を呼び出す `test.c` を作成: `gcc ft_list_foreach.c test.c -o test && ./test`

補足: コマンドはリポジトリのルートから実行してください。
