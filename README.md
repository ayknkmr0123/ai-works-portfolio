# AI Works Portfolio

生成AIを活用して制作した成果物をまとめた、1ページ完結のポートフォリオサイトです。

🔗 **公開URL**: https://ayknkmr0123.github.io/ai-works-portfolio/

## 特徴

- **1ページ・スクロールなし**：ファーストビューで全作品を一覧
- **クリックで拡大**（ライトボックス：背景クリック・×ボタン・Escキーで閉じる）
- **キーボード操作対応**（Tab で移動、Enter/Space で拡大）
- **レスポンシブ**：狭い画面では縦積み＋スクロールに自動切替

## デザイントーン

`design_prompt_unikoukokun.yaml` を基にした「あたたかいポップ」トーン。

- 土台：あたたかいクリーム地（`#fff6ef`）
- 主役：ビビッドなマゼンタピンク（`#ff2e8b`）
- 差し色：オレンジ／アンバー／パープル
- 見出しはピンク→パープルのグラデ文字、ピル型タグ

## 構成

```
.
├── index.html            # サイト本体（CSS/JS インライン・外部依存なし）
├── images/
│   ├── work-tetris.png   # ネオン・テトリス（Made with Manus）
│   └── work-ai-tools.png # 主要AIツール5選 インフォグラフィック（NotebookLM）
└── README.md
```

## 作品の追加方法

1. `images/` に画像を追加
2. `index.html` の `<figure class="card">` を1つコピー
3. `data-img` / 画像の `src`・`alt` / タイトル / タグを差し替え

> 1ページ・スクロールなしを保つなら作品は4点程度が上限です。

## デプロイ

`master` ブランチへ push すると GitHub Pages が自動でビルド・公開します。
