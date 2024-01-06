# da モジュール

`da` モジュールにはアバター定義に含まれるオブジェクトを返す関数が定義されています。
原則として定義ファイル先頭で `(use da :self)` と記述し、全てモジュール名を含めた名前で記述します。

## 各関数の記法について

* `:foo <value>` のようにコロンで始まる識別子を指定するものはキーワード引数です。
    - 後続の値 1 つとセットで解釈されます。
    - キーワード引数間の順序は自由です。
    - 必須の引数とは個別に順序が解釈されるので、必須の引数の手前に配置することも可能です。
* 末尾の引数で任意個の値を取る関数は、リストを渡すと全て *flatten (平坦化)* されて解釈されます。
    - 末尾の引数をリストから構成するために `apply` オペレーターを使用する必要はありません
    - リストではない値が出現するまで無限に展開されます。

## [アバター定義関数](./avatar.md)

* da/avatar
* da/parameters
* da/assets
* da/exports
* da/menu
* da/fx-controller

## [パラメーター定義関数](./parameters.md)

* da/bool
* da/int
* da/float

## [アセット定義関数](./assets.md)

* da/material
* da/animation

## [エクスポート定義関数](./exports.md)

* da/gate
* da/guard

## [メニュー定義関数](./menu.md)

* da/submenu
* da/button
* da/toggle
* da/radial
* da/two-axis
* da/four-axis
* da/axis

## [レイヤー定義関数 (基本)](./layer-basic.md)

* da/group-layer
* da/switch-layer
* da/puppet-layer
* da/option
* da/set-shape
* da/set-object
* da/set-material

## [レイヤー定義 (特殊)](./layer-raw.md)

* da/raw-layer
* da/clip
* da/inline-animation
* da/blendtree
* da/blendtree-field
* da/transition-to
* da/cond-eq
* da/cond-ne
* da/cond-gt
* da/cond-lt
* da/cond-ze
* da/cond-nz
