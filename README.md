# zenn-latesttech-genai
Zennで最新技術記事を生成AIを使って作る実験用リポジトリ

## ディレクトリ構成

```
.
├── articles/          # Zenn記事を格納するディレクトリ
│   └── sample-genai-article.md  # サンプル記事
├── LICENSE
└── README.md
```

## 記事の作成方法

1. `articles/` ディレクトリに新しいマークダウンファイルを作成します
2. ファイル名は `your-article-slug.md` の形式で命名します
3. 以下のようなfrontmatterを記事の先頭に追加します：

```yaml
---
title: "記事のタイトル"
emoji: "😊"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["トピック1", "トピック2"]
published: false # 公開する場合は true
---
```

## 参考リンク

- [Zenn CLIの使い方](https://zenn.dev/zenn/articles/zenn-cli-guide)
- [Zennのマークダウン記法](https://zenn.dev/zenn/articles/markdown-guide)
