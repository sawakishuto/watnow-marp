# watnow-marp

Marp を使ったプレゼンテーション作成プロジェクト

## セットアップ

```bash
npm install
```

## 使い方

### プレビュー（ブラウザで確認）

```bash
npm run preview
```

### ファイル監視モード

```bash
npm start
```

### ビルド

```bash
# HTML出力
npm run build

# PDF出力
npm run build:pdf

# PowerPoint出力
npm run build:pptx
```

## ディレクトリ構成

```
watnow-marp/
├── slides/          # スライドのMarkdownファイル
│   └── example.md   # サンプルスライド
├── themes/          # カスタムテーマ
│   └── custom.css   # カスタムテーマ例
├── dist/            # ビルド出力先
├── marp.config.mjs  # Marp CLI設定
└── package.json
```

## カスタムテーマの使用

スライドのフロントマターで指定:

```markdown
---
marp: true
theme: custom
---
```

## 参考リンク

- [Marp 公式サイト](https://marp.app/)
- [Marp CLI ドキュメント](https://github.com/marp-team/marp-cli)
- [Marpit Markdown](https://marpit.marp.app/markdown)
# watnow-marp
