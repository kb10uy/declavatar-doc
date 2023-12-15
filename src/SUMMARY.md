# Summary

[declavatar について](./README.md)

--------

# Unity で利用する

- [インストール](./on-unity-usage/installation.md)
- [Unity エディタ拡張](./on-unity-usage/editor-extension/README.md)
    - [GenerateByDeclavatar](./on-unity-usage/editor-extension/generate-by-declavatar.md)
    - [ExternalAsset](./on-unity-usage/editor-extension/external-asset.md)
    - [設定](./on-unity-usage/editor-extension/settings.md)

--------

# アバター定義

- [アバター定義とは](./avatar-definition/basic/README.md)
    - [パラメーター定義](./avatar-definition/basic/parameters.md)
    - [外部アセット定義](./avatar-definition/basic/assets.md)
    - [FX Layer 定義](./avatar-definition/basic/fx-controller.md)
    - [メニュー定義](./avatar-definition/basic/menu.md)
- [アバター定義詳細: レイヤー](./avatar-definition/layers/README.md)
    - [Group レイヤー](./avatar-definition/layers/group-layer.md)
    - [Switch レイヤー](./avatar-definition/layers/switch-layer.md)
    - [Puppet レイヤー](./avatar-definition/layers/puppet-layer.md)
    - [Raw レイヤー](./avatar-definition/layers/raw-layer.md)

--------

# 定義ファイルの各形式

- [定義ファイル (S 式)](./declaration-file/sexpr/README.md)
    - [構造](./declaration-file/sexpr/structure.md)
    - [`da` モジュール](./declaration-file/sexpr/da-module/README.md)
        - [da/avatar](./declaration-file/sexpr/da-module/avatar.md)
        - [da/parameters](./declaration-file/sexpr/da-module/parameters.md)
        - [da/assets](./declaration-file/sexpr/da-module/assets.md)
        - [da/fx-controller](./declaration-file/sexpr/da-module/fx-controller.md)
        - [da/menu](./declaration-file/sexpr/da-module/menu.md)
    - [`da-internal` モジュール](./declaration-file/sexpr/da-internal-module/README.md)

--------

# アバター定義サンプル

- [アバター定義の基本的な例](./declaration-file/examples/basic.md)
- [アバター定義の発展的な例](./declaration-file/examples/extra.md)

--------

# declavatar を拡張する

- [declavatar コア機能の拡張](./development/core/README.md)
    - [定義ファイル形式の追加](./development/core/add-format.md)
    - [操作対象の追加](./development/core/add-target.md)
- [declavatar 拡張ライブラリの定義](./development/extension-library/README.md)
