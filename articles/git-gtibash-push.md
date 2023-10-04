---
title: VS codeでターミナルを使わずにPushをする" # 記事のタイトル

emoji: "👩‍🚀" # アイキャッチとして使われる絵文字（1文字だけ）

type: "tech" # tech: 技術記事 / idea: アイデア記事

topics: ["iam", "github"] # タグ。["markdown", "rust", "aws"]のように指定する

published: false # 公開設定（falseにすると下書き）
---

## はじめに

### 【目標】

VisualStudioCode で Push をして、github や zenn に変更内容を保存・更新する。

### 【必要なもの】

- github 上のリポジトリ
- VisualStudioCode
- push したいフォルダーまたはファイル

### 【覚えておきたい単語】

- comit：ソースコードをリポジトリに更新する作業

- push:ローカルリポジトリ(自分の PC 内のみ)の内容をリモートリポジトリ(github などオンライン上)に送る

## 手順


1. visualstudiocode を起動して、push したいファイルを開く

2. 画面左側にあるソース管理のアイコンをクリックする

   ![push画面を表示する](../images/kanrigamen.png)

3. push したいファイルの横にある`＋`を押して、状態を`変更`から`ステージされている変更`へ移動させる

   ![変更前](../images/tuika_befor.png)

   ![変更後](../images/tuila_after.png)

4. `メッセージ`の入力をする(画像内で"push test"と記述されている部分)

   ![pushをする](../images/push.png)

5.` コミット`ボタンの横にある`✔`をクリックする
　 →`コミットしてプッシュ`を選択

6. 終了！
   github や zenn をリロードして、内容が変更されているか確認をしてみましょう
