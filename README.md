# Automagi共通資産

## 目的

このOrganizationは、当社で開発したプログラムを再利用可能にすることで、開発効率の向上を目指しています。

## お問い合わせ

このリポジトリにIssueを作成し井上(daiki-inoue)をアサインしてください。  
ルール改善の提案PRなどもお待ちしております。  
なお、特定のリポジトリに関する問題は各リポジトリにIssueを作成してください。

## 使い方

案件で使用する場合は案件別Organizationにforkしてください。  
汎用的な改修ができた場合は本Organizationに対しPRを作成してください。

## ルール

利便性と検索性を高めるために以下のルールは必ずお守りください。

### リポジトリ名

ケバブケースで簡潔に英語で命名してください。  
違反しているものがあった場合は発見次第修正させていただきます。

### トピック

検索性を高めるために必ずトピックを設定してください。  
トピックは以下のものを使用してください。  

| ジャンル               | topic                    | 概要                  |
| ---------------------- | ------------------------ | --------------------- |
| AMY内での領域          | agent                    | AMY Agent 関連        |
|                        | insight                  | AMY Insight 関連      |
| 扱うデータの種類       | text                     | テキストを取り扱う    |
|                        | image                    | 画像を取り扱う        |
|                        | video                    | 動画を取り扱う        |
|                        | point-cloud              | 点群を取り扱う        |
| 画像系リポジトリの分類 | image-augmentation       | 画像のデータ拡張      |
|                        | image-classification     | 画像分類              |
|                        | object-detection         | 物体検出              |
|                        | semantic-segmentation    | Semantic Segmentation |
|                        | instance-segmentation    | Instance Segmentation |
|                        | pose-estimation          | 骨格認識              |
| 点群系リポジトリの分類 | 3d-semantic-segmentation | 点群データの分類      |

### README

必ず `README.md` を作成してください。  
READMEの内容は[テンプレート](templates/README.md)を参照してください。
