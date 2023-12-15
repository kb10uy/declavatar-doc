# 定義ファイル (S 式)

declavatar 0.20.0 現在、メインでサポートされている定義ファイル形式は S 式です。
実行エンジンに [Ketos](https://github.com/murarth/ketos) を採用しており、Lisp や Scheme と同じような演算子や特殊形式を利用することができます。

* クォート、準クォート <code>' \` , ,@</code>
* `define lambda const`
* 末尾再帰最適化

全ての利用可能な記法については [Ketos Language Documentation](https://github.com/murarth/ketos/blob/master/docs/README.md) を参照してください。
