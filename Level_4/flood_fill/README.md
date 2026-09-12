## 課題

```BASH
演習名 : flood_fill
提出ファイル : *.c, *.h
使用可能な関数 : -
--------------------------------------------------------------------------------

`char **` 型で2次元の文字配列を表す引数、その配列の大きさを表す `t_point`、そして
開始地点を示す `t_point` を受け取る関数を書いてください。

渡された開始地点の `t_point` から、この関数は1つの領域全体を `'F'` という文字に
置き換えて塗りつぶします。「領域」とは、同じ文字が水平・垂直方向に他の文字や配列の
端で区切られたグループのことです。

`flood_fill` 関数は斜め方向には塗りつぶしを行いません。

`flood_fill` 関数は次のようにプロトタイプ宣言してください：
  void  flood_fill(char **tab, t_point size, t_point begin);

構造体 `t_point` は次のように定義されています：

  typedef struct  s_point
  {
	int           x;
	int           y;
  }               t_point;

例:

$> cat test.c
#include <stdlib.h>
#include <stdio.h>
#include "flood_fill.h"

char** make_area(char** zone, t_point size)
{
	char** new;

	new = malloc(sizeof(char*) * size.y);
	for (int i = 0; i < size.y; ++i)
	{
		new[i] = malloc(size.x + 1);
		for (int j = 0; j < size.x; ++j)
			new[i][j] = zone[i][j];
		new[i][size.x] = '\0';
	}

	return new;
}

int main(void)
{
	t_point size = {8, 5};
	char *zone[] = {
		"11111111",
		"10001001",
		"10010001",
		"10110001",
		"11100001",
	};

	char**  area = make_area(zone, size);
	for (int i = 0; i < size.y; ++i)
		printf("%s\n", area[i]);
	printf("\n");

	t_point begin = {7, 4};
	flood_fill(area, size, begin);
	for (int i = 0; i < size.y; ++i)
		printf("%s\n", area[i]);
	return (0);
}

$> gcc flood_fill.c test.c -o test; ./test
11111111
10001001
10010001
10110001
11100001

FFFFFFFF
F000F00F
F00F000F
F0FF000F
FFF0000F
$>
```

**オフラインでのコンパイルとテスト**

- **コンパイル:** `gcc -Wall -Wextra -Werror flood_fill.c -o flood_fill`（テストファイルが提供されている場合は、そのテストと一緒にコンパイルしてください）
- **例:** `gcc flood_fill.c test.c -o test; ./test`

補足: コマンドはリポジトリのルートから実行してください。
