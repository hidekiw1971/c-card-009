# compornent（共通部品）

## イメージ画像
<img width="399" alt="image" src="https://user-images.githubusercontent.com/99580997/160555325-0ed1df21-08ec-4ee0-b9b3-319fb8a95848.png">
<img width="780" alt="image" src="https://user-images.githubusercontent.com/99580997/160555377-9d77a661-4c80-49b4-8f21-0d542ac1a3d2.png">
<img width="1167" alt="image" src="https://user-images.githubusercontent.com/99580997/160555633-ad0bb5f7-56ec-415d-ab92-15aab691c56e.png">

## 概要

- カード（画像（擬似要素）、タイトル、説明）
- `display: flex;`は使わず、`position: relative/absolute;`で実装してます。

## 仕様

- スマホファースト
- rem 記述
- ルートフォントを vw で設定していることから PC サイズのレイアウトをタブレットで表示させることが出来ます（rem で書いた場合のみ）。
- xxx

## 注意事項

- swiper は擬似要素では実装不可。

## 使い方

- 「copy start」から「copy end」をコピペ。
- css: src -> module -> box をコピペ。

## w3c html チェック結果

- https://validator.w3.org/nu/
<img width="762" alt="image" src="https://user-images.githubusercontent.com/99580997/160555717-ce694872-b686-48ca-bc9b-f31e4a6a6b4e.png">

## w3c css チェック結果

- https://jigsaw.w3.org/css-validator/
<img width="1545" alt="image" src="https://user-images.githubusercontent.com/99580997/160555776-c93faff6-b65a-4c40-9d9d-c9b2619ac354.png">

## portfolio url:

- https://c-0039.wtb.cfbx.jp/

## 参考にしたサイト

- CSS:難しい？意外と便利な position を使いこなそう
- https://www.koushinclub.com/blog/1453.html
- 【CSS】position の基本とよく使う使用方法まとめ
- https://b-risk.jp/blog/2021/09/position_basic/
- max-height(css 辞典)
- https://tinyurl.com/ybx43dsj
- CSS 擬似要素「before/after」の背景画像表示で鬼ハマリしたので備忘録メモ
- https://tinyurl.com/y8j7uexx
- flex-direction(mdn web docs)
- https://developer.mozilla.org/ja/docs/Web/CSS/flex-direction
- 見えない文字「U+0008」の潜伏場所を SublimeText と CotEditor で暴く方法
- https://tinyurl.com/ybdwzfot
- Visual Studio Code 設定 不可視文字・制御文字を表示させる
- https://www.programming-se.com/?p=4997
-

## 更新履歴

- 2022/3/29 初版 作成完了(カード（画像（擬似要素）、タイトル、説明）)

## 環境・使い方

- ダウンロードしたフォルダを開く。
- ターミナルを開き、 npm i とコマンドを入力する。
- node_modules と package-lock.json が生成されるのを確認する。
- 「 npx gulp 」とコマンドを入力すると動き出します。

## 備考
