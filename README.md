# 家づくり安心ローンシミュレーター 完全版

## 修正内容
- 既存機能は削除せず、IE-LOGバナー画像の読み込み部分だけ修正。
- 外部URLの jpg 参照をやめ、同梱した `images/myhomeheroes.png` を参照。
- 画像読み込み失敗時も、テキストバナーが表示される fallback を追加。
- バナークリック計測 `ielog_banner_clicked` を追加。

## 配置方法
Cloudflare Pages / 静的ホスティングでは、`index.html` と `images/myhomeheroes.png` を同じ階層構造のままアップロードしてください。

```
root/
├─ index.html
└─ images/
   └─ myhomeheroes.png
```
