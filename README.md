# UGATTA preview

このフォルダは GitHub Pages の確認用です。検索エンジンに登録されにくいよう `noindex` と `robots.txt` を設定し、CNAME は含めていません。

GitHub Pages: Deploy from a branch / main / (root) で公開してください。

# UGATTA Website

合同会社UGATTAの公式サイトです。GitHub Pagesで公開します。

## 公開URL
- https://ugatta-llc.com/

## 更新・デプロイ
GitHub Pages の **Deploy from a branch** を使い、`main` ブランチの `/ (root)` を公開します。`main` へ push すると自動的に反映されます。

```powershell
git add .
git commit -m "Update website"
git push
```

## SEO / AI検索向け実装
- ページ固有の title / meta description
- canonical / OGP / Twitter Card
- Organization / WebSite / Service / BreadcrumbList 構造化データ
- XML sitemap / robots.txt
- `llms.txt`（補助的なAIクローラー向けサイト要約）
- セマンティックHTML、明確な見出し階層、内部リンク
- 表示コンテンツと一致する簡潔なQ&A
- 画像alt、遅延読み込み、モバイル対応

## Analytics
Google tag: `G-QS9HSHCY33`
