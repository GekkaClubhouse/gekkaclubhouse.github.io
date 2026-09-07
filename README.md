# 月華クラブハウス / GEKKA CLUBHOUSE

中島ミア＆リサ、五十嵐エマ、マユ、長田リオを紹介するホームページです。
日本語・英語に対応しています。マユは陸上・ダンス、リオはバレーボール、ミア＆リサとエマは陸上です。

公開サイト: https://gekkaclubhouse.github.io/

## SNSリンクの編集方法

1. このリポジトリの `social-links.js` を開き、鉛筆マーク（Edit this file）を押します。
2. 編集したいメンバーの項目で、空の `""` の間にURLを貼ります。
3. **Commit changes… → Commit changes** で保存します。GitHub Pagesへの反映後、リンクが有効になります。

例（URLは実際のアカウントに置き換えてください）:

```js
"instagram": "https://www.instagram.com/自分のユーザー名/"
```

- `mia-risa`: 中島ミア＆リサ。`instagram`、`x`、`tiktok`、`vip` の4項目。
- `emma`: 五十嵐エマ。`instagram`、`vip` の2項目。
- `mayu` / `rio`: それぞれ `instagram`、`vip` の2項目。
- `vip` にVIP LoungeのURLを貼ります。
- 引用符やカンマを残し、`https://` から始まるURLを貼ってください。
- URLを空欄に戻すとリンクは無効になります。URLの入力だけで準備中の項目も有効になるので、別の設定変更や再ビルドは不要です。
- 更新が見えない場合は少し待ってからページを再読み込みしてください。

## 個別ページ

- [中島ミア＆リサ](https://gekkaclubhouse.github.io/mia-risa.html)
- [五十嵐エマ](https://gekkaclubhouse.github.io/emma.html)
- [マユ](https://gekkaclubhouse.github.io/mayu.html)
- [長田リオ](https://gekkaclubhouse.github.io/rio.html)

全ページで日本語・英語を切り替えられます。言語は個別ページ間の移動にも引き継がれます。

デザインやコードを更新するときは、GitHub上で編集した最新の `social-links.js` を必ず引き継いでください。

## GitHub Pagesで公開する場合

このフォルダの内容をリポジトリのルートに配置します。
GitHubの **Settings → Pages → Deploy from a branch** で **main / (root)** を選択します。
`.nojekyll`、`assets`、`images` を含む全ファイルが必要です。

ユーザーサイトはリポジトリ名を `ユーザー名.github.io` にします。
プロジェクトサイトとして公開する場合も、相対パスのためそのまま動作します。

## 表示言語

ページ右上のメニューで日本語と英語を切り替えられます。
URLに `?lang=en` を付けると英語で表示します。

画像は提供された素材を使用しています。
