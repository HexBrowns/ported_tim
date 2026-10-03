# HexBrowns による追加

このフォークは Nanashi. さんの [ported_tim](https://github.com/sevenc-nanashi/ported_tim)（原作はティム さんのスクリプト） に、HexBrowns が改変したスクリプトを足したものです。
元のファイルは変えていません。追加したファイルは、すべてこの `HexBrowns/` フォルダにあります。

| ファイル | 内容 | 説明書 |
|---|---|---|
| `放射分布_H.anm2` | `@tim.anm2.anm2` の「放射分布」を軽くした版。設定項目は原作と同じ | [docs](docs/放射分布_H.md) |
| `オートターゲット_H.cam2` | ティム さんの「オートターゲット」を元にしたカメラ効果。`座標公開_H.anm2` と組で使う | [docs](docs/オートターゲット_H.md) |
| `座標公開_H.anm2` | オートターゲット_H のターゲットに掛け、動かした後の位置をカメラへ渡す | — |

## 導入

`Script/` の中身を、AviUtl2 の `Script` フォルダ（既定は `C:\ProgramData\aviutl2\Script`）へコピーして、AviUtl2 を起動し直します。
元のスクリプトとは別の名前なので、並べて置けます。

## ライセンス

MIT（このリポジトリの `LICENSE` と同じ。追加分は Copyright (c) 2026 HexBrowns）

HexBrowns のほかのスクリプトは [HexBrowns/HexScript](https://github.com/HexBrowns/HexScript) にあります。
