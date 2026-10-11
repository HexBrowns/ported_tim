# HexBrowns による追加

`ティムさん` のスクリプトをAviUtl2用に移植した `Nanashi.さん` の [ported_tim](https://github.com/sevenc-nanashi/ported_tim) をフォークしたものです。

| ファイル              | 内容                                        | 説明書                        |
| ----------------- | ----------------------------------------- | -------------------------- |
| `放射分布_H.anm2`     | `@tim.anm2.anm2` の「放射分布」を軽くした版            | [docs](docs/放射分布_H.md)     |
| `オートターゲット_H.cam2` | 「オートターゲット」を元にしたカメラ効果で `座標公開_H.anm2` と組で使用 | [docs](docs/オートターゲット_H.md) |
| `座標公開_H.anm2`     | オートターゲット_H のターゲットに掛け、動かした後の位置をカメラへ渡す      | —                          |

## 導入

使用したいスクリプトを `Script` から取り出し、AviUtl2の `Script` フォルダへコピーし、AviUtl2を起動します。
元のスクリプトとは名称が違うため競合の心配は不要です。

## ライセンス

MIT

他のスクリプトは [HexBrowns/HexScript](https://github.com/HexBrowns/HexScript) にあります。
