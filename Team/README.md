# GitHub ワークショップ チーム開発

GitHub を用いたチーム開発について一通りの手順を体験してもらう内容になっています。  
チームメンバー間の GitHub への理解度をチーム内で共有するために使用してください。

## 資料概要
```
.
├── README.md //この資料
├── githubws_team.pdf // チーム開発のみの資料
├── githubws_allin.pdf // 基礎編とチーム開発編を合わせた資料
├── hands-on.zip // 演習で使用するプログラムをまとめたzipファイル
└── setup_team.pdf // チーム開発のセットアップ資料 
```

## 学習の進め方

### 前提知識

**チームメンバーの全員が「GitHub への add/commit/push」と「branch 作成 ~ PR の作成」を行える必要があります。**

前提知識ついて学ぶ際は以下の資料を参考にしてください。
- 推奨環境（VSCode環境）は[こちら](https://github.com/hackujp/github_tutorial/tree/main/ver_VSCode/)
- CUI（MacOSのみ）は[こちら](https://github.com/hackujp/github_tutorial/tree/main/ver_CUI/)

### 事前準備

**Gitの環境構築を行っていない方**は、[こちら](https://github.com/hackujp/github_tutorial/tree/main/Basics)のREADMEを参考に環境構築を行ってください

チーム開発演習の準備として[セットアップ資料](./setup_team.pdf)を参考に、以下の事前準備を行ってください。

- [GitHub](https://github.co.jp/) でチーム共有のリポジトリ作成
- 作成したリポジトリにチームメンバーをアサイン
- [演習ファイル](./team_hands-on.zip)を解凍して、作成したリポジトリに push
- チームメンバー全員のローカルリポジトリの作成

準備が完了したら、[学習資料](./githubws_allin.pdf) の資料をダウンロードしておきましょう。

### メイン資料の内容

#### Git/GitHubの基本機能おさらい（[ver_VScode](https://github.com/hackujp/github_tutorial/blob/main/Basics/githubws_vscode.pdf)の内容になります）
- Gitとは
- GitHubの基本操作（clone, add, commit, push）
- 作業用ブランチの作成 （ブランチ, チェックアウト）
- mainブランチに変更を反映する（Pull Request, pull）

#### GitHub をチームで使うには
- GitHubをチームで使う
- Conflict について
	- Conflictを起こさない
	- Conflictの解消方法

#### チーム演習  
**Webページ で動く電卓 をチーム開発**  
JavaScript を使ったサンプルプログラムに追加の実装をして電卓アプリを作成します。  
手順や実装コードは資料内に記載してありますので、JavaScript 未経験でも問題はありません。  

**進め方**  
チーム内で役割を決め、作業を行っていきます。

分担の例: 
- コーダー 2人
- レビュアー 1人以上

1. 演習開始時に指定されたブランチを作成
2. コーダーはそれぞれ並列で指定されたコードを実装して、PR を作成
3. PR をレビュアーが確認
	1. Conflict やその他修正箇所があればコメントで指摘
	2. 修正箇所が合った場合はそれぞれの実装者が修正して再度レビュー
4. すべての実装が済んだら、index.html を手元のブラウザで動作確認

この演習は複数人で作業することを前提とした作りになっています。  
個人で行う際には、ブランチを切り替えて行うことで学習可能です。

#### Appendix
- gitignore の使い方
- ロールバック
- ブランチの使い方
- コードレビューについて
