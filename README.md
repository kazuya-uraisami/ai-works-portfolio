# AI.Works Portfolio

生成AIを活用した業務自動化・チャットボット・情報配信システムの開発実績ポートフォリオサイト。

🌐 **公開URL**: https://kazuya-uraisami.github.io/ai-works-portfolio/

## 概要

- **デザインテーマ**: Trust Corporate Clean（白基調・ネイビー/スレート差し色の信頼感あるコーポレートデザイン）
- **構成**: Hero / Works（制作実績）/ About / Contact
- **技術**: 静的HTML + CSS（単一ファイル・依存なし）、レスポンシブ対応

## 実績の追加方法

`index.html` の `WORKS` セクション内、`.ph`（点線の追加枠）を以下のカードに置き換えるだけで実績を追加できます。

```html
<a class="card" href="image/ファイル名.PNG" target="_blank">
  <div class="thumb"><img src="image/ファイル名.PNG" alt="案件名"></div>
  <div class="card-body">
    <div class="tags">
      <span class="tag">タグ1</span>
      <span class="tag">タグ2</span>
    </div>
    <h3>案件タイトル</h3>
    <p>案件の概要説明。</p>
  </div>
</a>
```

スクリーンショット画像は `image/` フォルダに置きます。

## ローカルプレビュー

```bash
python -m http.server 8765
# → http://localhost:8765/
```

## デプロイ

`main` ブランチへの push で GitHub Pages に自動公開されます（Settings → Pages → Source: `main` / root）。
