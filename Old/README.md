# こちらの資料は非推奨です

下記のリンクから別のツールを使う資料を参考にしてください。

推奨環境はVSCodeを用いたものになっています。

- [ver_VSCode](../ver_VSCode): Windows/MacのVisual Studio Code環境
- [ver_CUI](../ver_CUI): Macのターミナル環境


# GitHub ワークショップ GUI版

## 資料概要

```
.
├── README.md //この資料
├── githubws_gui.pdf // メイン資料
├── hands-on.zip // 演習で使用するプログラムをまとめたzipファイル
├── setup_sourcetree_mac.pdf // セットアップ資料(MacOS版)
├── setup_sourcetree_mac_for_event.pdf // イベント参加者向けセットアップ資料(MacOS版)
├── setup_sourcetree_windows.pdf // セットアップ資料(Windows版)
└── setup_sourcetree_windows_for_event.pdf // イベント参加者向けセットアップ資料(Windows版)
```

## 学習の進め方

### 事前準備

#### 独自で学びたい方へ

セットアップ資料 ([Windows](./setup_sourcetree_windows.pdf), [MacOS](./setup_sourcetree_mac.pdf)) を参考に、以下の事前準備を行ってください。

- [GitHub](https://github.co.jp/) のアカウント作成
- [Sourcetree](https://www.sourcetreeapp.com/) のインストール
- 演習準備
- GitHubへの疎通確認

準備が完了したら、[学習資料](./githubws_gui.pdf) をダウンロードして、学習しましょう。


#### イベント参加者の方へ

イベントに参加される方は、こちらのセットアップ資料([Windows](./setup_sourcetree_windows_for_event.pdf), [MacOS](./setup_sourcetree_mac_for_event.pdf)) を参考に、上記に追加で準備を行ってください。

- [zoom](https://zoom.us/) のセットアップ
- slack のセットアップ
  - 招待リンクは connpass で登録後にご連絡します。
  
準備が完了したら、[学習資料](./githubws_gui.pdf) の資料をダウンロードしておきましょう。

### メイン資料の内容

#### Step.1 GitHubの基本動作

- README.mdを作成/index.html を編集してみよう
- 作成/変更したファイルを add してみよう
	- 変更したファイルの差分を確認しよう
- インデックスされたファイルを commit してみよう
	- コミットメッセージを他の人が見て、わかりやすいように意識して記述しよう
- ローカルリポジトリの変更 を push してみよう
- リモートリポジトリを確認してみよう
	- コミットツリーを確認してみよう

#### Step.2 作業ブランチを作成して、変更内容の Pull Request を作成

##### Step.2-1 作業ブランチを作成し、ファイルを Push
- ブランチを作成してみよう
- 作業ブランチでファイルを更新して Push してみよう
- GitHub で作成したブランチと push したファイルを確認しよう
 
##### Step.2-2 Pull Request を作成して master に反映
- GitHub で Pull Request を作成してみよう
- Pull Request の中身を確認しよう
	- こだわった点をコメントしよう
- Pull Request を merge しよう
	- GitHub 上で master ブランチのファイル内容を確認しよう
- ローカルリポジトリの master ブランチを更新するため Pull しよう
	- ローカルリポジトリで master ブランチの変更を確認しよう

## 参考資料リンク
- [サル先生のGit入門](https://backlog.com/ja/git-tutorial/)
- [git Book 日本語版](https://git-scm.com/book/ja/v2)
