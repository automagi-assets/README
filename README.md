# Automagi 共通資産

## 目的

この Organization は、当社で開発したプログラムを再利用可能にすることで、開発効率の向上を目指しています。

## お問い合わせ

このリポジトリに Issue を作成し井上(daiki-inoue)をアサインしてください。  
ルール改善の提案 PR などもお待ちしております。  
なお、特定のリポジトリに関する問題は各リポジトリに Issue を作成してください。

## 使い方

案件で使用する場合は案件別 Organization に fork してください。  
汎用的な改修ができた場合は本 Organization に対し PR を作成してください。

## ルール

利便性と検索性を高めるために以下のルールは必ずお守りください。

### リポジトリ名

ケバブケースで簡潔に英語で命名してください。  
違反しているものがあった場合は発見次第修正させていただきます。

### トピック

検索性を高めるために必ずトピックを設定してください。  
トピックは以下のものを使用してください。

| ジャンル               | topic                    | 概要                   |
| ---------------------- | ------------------------ | ---------------------- |
| AMY 内での領域         | agent                    | AMY Agent 関連         |
|                        | insight                  | AMY Insight 関連       |
| 扱うデータの種類       | text                     | テキストを取り扱う     |
|                        | image                    | 画像を取り扱う         |
|                        | video                    | 動画を取り扱う         |
|                        | audio                    | 音響信号を取り扱う     |
|                        | point-cloud              | 点群を取り扱う         |
|                        | time-series              | 時系列データを取り扱う |
| 画像系リポジトリの分類 | image-augmentation       | 画像のデータ拡張       |
|                        | image-classification     | 画像分類               |
|                        | object-detection         | 物体検出               |
|                        | semantic-segmentation    | Semantic Segmentation  |
|                        | instance-segmentation    | Instance Segmentation  |
|                        | pose-estimation          | 骨格認識               |
|                        | image-generator          | 画像生成               |
| 点群系リポジトリの分類 | 3d-object-detection      | 点群データの物体検出   |
|                        | 3d-semantic-segmentation | 点群データの分類       |

### README

必ず `README.md` を作成してください。  
README の内容は[テンプレート](templates/README.md)を参照してください。
