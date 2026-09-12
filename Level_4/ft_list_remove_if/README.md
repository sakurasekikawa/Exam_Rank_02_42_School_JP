## 課題

```BASH
演習名 : ft_list_remove_if
提出ファイル : ft_list_remove_if.c
使用可能な関数 : free
--------------------------------------------------------------------------------

`ft_list_remove_if` という名前の関数を書いてください。この関数は、引数として渡さ
れたリストから、`data` フィールドが基準値と「等しい」すべての要素を削除します。

関数は次のように宣言されています：

void ft_list_remove_if(t_list **begin_list, void *data_ref, int (*cmp)());

`cmp` は2つの `void *` を受け取り、2つの引数が等しいとみなされる場合に `0` を
返します。

次の `ft_list.h` ファイルを使用してください：

$>cat ft_list.h
typedef struct      s_list
{
    struct s_list   *next;
    void            *data;
}                   t_list;
$>
```

**オフラインでのコンパイルとテスト**

- **コンパイル:** `gcc -Wall -Wextra -Werror ft_list_remove_if.c -o ft_list_remove_if`（テストファイルが提供されている場合は、そのテストと一緒にコンパイルしてください）
- **例:** `ft_list.h` をインクルードし `ft_list_remove_if` を呼び出す `test.c` を作成: `gcc ft_list_remove_if.c test.c -o test && ./test`

補足: コマンドはリポジトリのルートから実行してください。
