# RYUGE COFFEE Links

名刺サイズの紙やショップカードに載せる QR コードのリンク先として使う、1 ページだけの静的サイトです。

## Links

- Online Shop: `https://www.ryuge.biz`
- Instagram: `https://www.instagram.com/ryuge_coffee/`
- Google Review: `https://g.page/r/CdPPvYlcn7PqEBM/review`

## Local Preview

`index.html` をブラウザで開くだけで確認できます。

## Deploy To Vercel

1. Vercel で新規プロジェクトを作成します。
2. Project Root / Root Directory に `ryuge-coffee-links` を指定します。
3. Framework Preset は `Other` または `No Framework` を選びます。
4. Build Command は空欄のままで問題ありません。
5. Output Directory も空欄のままで問題ありません。
6. Deploy を実行します。

このフォルダには静的配信用の `vercel.json` も含めています。ビルド処理は不要です。

リンク先を変更したい場合は、`index.html` 内の `<a>` タグの `href` を編集してください。
