# SEO / AI検索対応メモ

## 実装済み

- 全主要ページに固有の `<title>` と meta description
- canonical URL を `https://ugatta-llc.com/` 側へ統一
- OGP / Twitter Card と 1200×630 の `og-image.jpg`
- Organization / WebSite / Service / BreadcrumbList の JSON-LD
- 見出し階層（各ページの H1 は1つ）とセマンティックHTMLの整理
- 内部リンクとパンくず
- `robots.txt` / `sitemap.xml` の更新
- `llms.txt` の追加（AIクローラー向けの補助情報。標準SEOの代替ではありません）
- 画像 alt、width / height、lazy loading
- 外部Webフォント依存を削除し、表示速度を改善
- モバイルナビ、キーボード操作、reduced motion 対応
- 404ページに `noindex,follow`
- Google Tag を全ページで `GT-M3S9S5D7` に統一
- お問い合わせ / 無料ツールのクリックイベント計測用フックを追加

## 公開後に行うこと

1. GitHub Pages で本番表示・HTTPSを確認
2. Google Search Console で `https://ugatta-llc.com/sitemap.xml` を送信
3. URL検査からトップ、事業内容、支援事例、無料ツールの再クロールをリクエスト
4. 構造化データを Rich Results Test / Schema Markup Validator で確認
5. PageSpeed Insights でモバイル表示を確認
6. GAで `contact_click` / `tool_click` が取得できるか確認

## 今後、特に効く改善

- 匿名事例にも「どの業務時間がどれだけ減ったか」「OTA掲載数」「問い合わせ増加」など、公開可能な一次情報・数値を追加
- 宿泊DX、PMS選定、インバウンドOTA、業務改善などの実務記事を継続公開
- 会社・代表・支援方針の一次情報を充実させ、UGATTAというエンティティを明確化
- 支援事例を増やし、各テーマからサービスページへ内部リンク

## AIOについて

GoogleのAI Overview / AI Mode向けに特別なタグを追加するのではなく、検索エンジンがアクセスできること、独自性のある役立つ本文、明確なページ構造、表示内容と一致する構造化データを優先しています。

2026年5月にGoogleはFAQリッチリザルトを廃止したため、今回は読みやすいQ&A本文は設置しつつ、FAQPage構造化データはあえて入れていません。
