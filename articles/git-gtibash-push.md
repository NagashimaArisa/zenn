---
title: VS codeでターミナルを使わずにPushをする" # 記事のタイトル

emoji: "👩‍🚀" # アイキャッチとして使われる絵文字（1文字だけ）

type: "tech" # tech: 技術記事 / idea: アイデア記事

topics: ["aws", "iam", "github"] # タグ。["markdown", "rust", "aws"]のように指定する

published: false # 公開設定（falseにすると下書き）
---

## はじめに

【目標】
VisualStudioCode でPushをして、github や zenn に変更内容を保存・更新する。

【必要なもの】
・github上のリポジトリ
・VisualStudioCode
・push したいフォルダーまたはファイル

【単語】
- comit：ソースコードをリポジトリに更新する作業

- push:ローカルリポジトリ(自分のPC内のみ)の内容をリモートリポジトリ(githubなどオンライン上)に送る

## 手順

1. visualstudiocode を起動して、push したいファイルを開く

2. ソース管理のアイコンをクリックする

   ![push画面を表示する](https://github.com/NagashimaArisa/zenn/blob/81dcbe54f58c0e0afba873bffd447a8839017bc8/images/kanrigamen.png)

3. push したいファイルの横にある`＋`を押して、状態を`変更`から`ステージされている変更`へ移動させる

   ![変更前](../images/tuika_befor.png)

   ![変更後](../images/tuika_after.png)

4. `メッセージ`の入力をする(画像内で"push test"と記述されている部分)

   ![pushをする](../images/push.png)

5.` コミット`ボタンの横にある`✔`をクリックする
　 →`コミットしてプッシュ`を選択

6. 終了！
githubやzennをリロードして、内容が変更されているか確認をしてみましょう

