# はじめる

## ページを追加する

1. `docs/` にMarkdownファイルを作成します。
2. `_sidebar.md` にページへのリンクを追加します。
3. ブラウザーでページを開いて表示を確認します。

たとえば `faq.md` を作ったら、サイドバーに次のリンクを追加します。

```text
- [よくある質問](faq.md)
```

## トップページを変更する

`README.md` がサイトのトップページです。プロジェクトの説明や、よく読んでほしいページへのリンクをここに書きます。

## Docsifyの設定

サイト名やサイドバーの設定は `index.html` の `window.$docsify` で変更できます。

```javascript
window.$docsify = {
  name: 'サイト名',
  loadSidebar: true,
  subMaxLevel: 2
}
```