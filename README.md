# 乃木坂46 フォーメーション作成シミュレーター 静的サイト版

Bubbleの代替として、維持費をほぼゼロにするための静的サイトです。

## 機能
- 1列目 / 2列目 / 3列目の人数変更
- メンバー検索
- クリックで自動配置
- 配置解除
- ブラウザ内保存 / 読込
- 共有用テキスト生成
- PNG保存
- メンバーデータJSON編集

## 公開方法
### 一番安い方法
GitHub Pages / Cloudflare Pages / Netlify / Vercel の無料枠に `index.html`, `styles.css`, `app.js` を置くだけです。

### 画像について
初期版は権利面を避けるため写真を同梱していません。
`app.js` の `image` に画像URLを入れるか、画面下のJSON編集欄から追加してください。

例:
```json
{"name":"井上 和","gen":"5期生","image":"https://example.com/nagi.jpg"}
```
