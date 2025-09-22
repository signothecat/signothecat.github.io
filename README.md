# スキル・ポートフォリオについて

## スキル
現在、以下のスキルを習得・学習しています。下にポートフォリオも掲載しています。
- HTML/CSS：アプリ開発で利用
- JavaScript：アプリ開発で利用
- TypeScript：アプリ開発（後述）で利用
- React Native：アプリ開発（後述）で利用
- Git：アプリ開発（後述）で利用
- Shell Script：ゲーム開発（後述）で利用
- WordPress：少し触れたことがある程度

また、以下のスキルについても学習経験があります。
- C++：大学の講義にて組み込みシステムのプログラミングを学習
- Unity・C#：高校生のときにUnityにてゲームを制作

## ポートフォリオ

以下は、開発スキルの学習・実践のために制作したアプリやツールです。  
主にWebアプリケーションやモバイルアプリを中心に、開発に取り組んできました。

### Color2Go/文字色と背景色を生成するツール
- 使用している技術スタック
  - HTML/CSS、JavaScript、Git、Vercel
- 概要
  - 背景色と文字色の組み合わせを作成し、可読性もチェックすることができる、ブラウザで動作するデザイン支援ツールです。
- デモ
  - [https://color2go.vercel.app/](https://color2go.vercel.app/)
- リポジトリ
  - [https://github.com/signothecat/color2go](https://github.com/signothecat/color2go)
- 工夫した・苦労した点
  - URLにカラーコードが反映されるようにし、色の組み合わせを保存・共有することができるようになっています。
  - レスポンシブ対応しています。

### 本の記録アプリ
- 使用している技術スタック
  - React Native、Expo、TypeScript、HTML/CSS、Git、npm、Node.js
- 概要
  - 読みたい本を登録したり、読書中の本を管理したりすることができる、iOSアプリです。
  - 実装している機能：バーコード読取での書籍検索・登録、読書状況（読みたい/読んだ等）の登録、本棚機能
- キャプチャ・スクリーンショット
  - 以下のリンク先で動作の様子を公開しています。
  - [https://github.com/user-attachments/assets/82749d2a-eea3-45e1-a971-bcf50fdfe0e5](https://github.com/user-attachments/assets/82749d2a-eea3-45e1-a971-bcf50fdfe0e5)
- 工夫した・苦労した点
  - Google Books API と OpenBD API の両方からデータを取得し、信頼性の高い情報を選択・統合する仕組みを実装しました。
  - バーコード読取画面にて、アンマウント時に非同期処理を停止する仕組みを組み込み、カメラ処理負荷によるアプリの強制終了を防止しました。
  - バーコード読取画面にて、API呼び出し中および登録済みのISBNを管理し、重複読取を回避することで安定した連続スキャンを実現しました。
  - 本棚画面にて、ローディング／エラー時も直前の一覧を保持することで再描画を最小化し、ちらつきを防止しました。
  - FlatListでuseCallbackを使用して描画関数をメモ化し、一覧スクロールのパフォーマンスを向上させました。

### 青空文庫リーダー/aozora-reader
- 使用している技術スタック
  - HTML、CSS、JavaScript、Git、Vercel
- 概要
  - ブラウザで動作する青空文庫のリーダーです。
  - 横書き/縦書き切替機能、ライト/ダークモード切替機能、余白調整機能などを実装しています。
- デモ
  - [https://aozora-reader-phi.vercel.app/](https://aozora-reader-phi.vercel.app/)
  - 注) 余白調整機能は作業中のため、まだ実装されていません
- リポジトリ
  - [https://github.com/signothecat/aozora-reader](https://github.com/signothecat/aozora-reader)
- 工夫した・苦労した点
  - 表示形式を共通して整えるために、本文ファイルを`.md`形式で管理し、`md-to-html.js`でパース、`novel-loader.js`で取得・表示するという仕組みを実装しました。

### forest-coffee
- 概要
  - 架空のクライアントを想定して制作した、WordPressのテンプレートです。
- 使用している技術スタック
  - WordPress、HTML/CSS、PHP、Local (by Flywheel)
- キャプチャ・スクリーンショット
  - 以下のリンク先でサイトのサンプル動画を公開しています。
  - [https://github.com/user-attachments/assets/1b03b85a-c359-4f3a-a7ae-34bf9839aea9](https://github.com/user-attachments/assets/1b03b85a-c359-4f3a-a7ae-34bf9839aea9)

## ポートフォリオ(その他)
### zsnake
- 概要
  - シェル(zsh)で遊ぶことができるヘビゲームです。
- 使用している技術スタック
  - zsh、Shell Script、Git
- リポジトリ
  - [z snake](https://github.com/signothecat/zsnake)（動作の様子もリポジトリでご確認いただけます）
