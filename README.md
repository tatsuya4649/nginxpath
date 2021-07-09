
# Nginx path tutorial

nginxの設定ファイルではlocationディレクティブでURIのパスごとの設定を記述することができる。

```

location / {
	(this is context of location)
}

```

nginxはこのlocationディレクティブに記載されたコンテキストを元にパスのルーティングをおこなう。

(ルーティング=>どのURLにしたがって、どのパスからファイルを返すのか？どのURLにしたがって、他のホストにプロキシするのか？など)
