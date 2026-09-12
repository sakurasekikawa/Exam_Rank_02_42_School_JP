## 課題

```BASH
演習名 : sort_int_tab
提出ファイル : sort_int_tab.c
使用可能な関数 : 
--------------------------------------------------------------------------------

次の関数を書いてください：

void sort_int_tab(int *tab, unsigned int size);

この関数は、ちょうど `size` 個の要素を含む整数配列 `tab` を、その場（in-place）で
昇順にソートしてください。

重複した値はそのまま保持してください。

入力は常に整合性のあるものとします。
```

**オフラインでのコンパイルとテスト**

- **コンパイル:** `gcc -Wall -Wextra -Werror sort_int_tab.c -o sort_int_tab`（テストファイルが提供されている場合は、そのテストと一緒にコンパイルしてください）
- **例:** `sort_int_tab` を呼び出す `test.c` を作成: `gcc sort_int_tab.c test.c -o test && ./test`

補足: コマンドはリポジトリのルートから実行してください。
