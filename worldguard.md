# WorldGuard の使い方

## 1. WorldGuard の導入方法
- WorldGuard を使うには、プラグインサーバー（例: **PaperMC** や **Spigot**）が必要です。
- また、WorldGuard の前提プラグインとして **WorldEdit** をインストールする必要があります。
- ダウンロードした WorldEdit と WorldGuard のファイルをサーバーの「plugins」フォルダに入れてください。

## 2. 保護エリアの指定
1. 木の斧を手に持ち、左クリックで起点、右クリックで終点ブロックを選択します。
2. 立方体の対角線を結ぶ形で起点と終点を設定してください。
3. コマンド `/rg define [リージョン名]` でリージョンを作成します。

## 3. メンバーの登録
- リージョンにプレイヤーをメンバーとして登録することで、リージョン内で建築などができるようになります。
- コマンド `/rg addmember [リージョン名] [プレイヤー名]` でメンバーを登録できます。

詳細な情報は公式ドキュメントを参照してください。

[WorldGuard 公式ドキュメント](https://worldguard.enginehub.org/en/latest/regions/commands/)
