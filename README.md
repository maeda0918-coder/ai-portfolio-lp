# AI活用ポートフォリオLP

mae のAI活用ポートフォリオ。プロフィール、AI活用テーマ、作ったもの、これから作りたいものをまとめた1枚のLPです。

**公開URL**：（Vercelで公開後にここへ追記）

## 構成

| セクション | 内容 |
|---|---|
| Hero | 名前とキャッチコピー |
| About | 自己紹介 |
| AI活用テーマ | いまAIを向けている3つの方向 |
| 作ったもの | 制作物（このLPを含む） |
| これから作りたいもの | 今後のテーマ |
| CTA | GitHubリポジトリへのリンク |

## 技術

- 単一 `index.html` のみ
- [Tailwind CSS](https://tailwindcss.com/)（CDN）
- ビルドツール・パッケージマネージャは不使用
- 画像なしで完結（アイコンは絵文字とインラインSVG）

## ローカルで見る

ビルド不要です。リポジトリを取得して `index.html` をブラウザで開いてください。

```bash
git clone https://github.com/maeda0918-coder/ai-portfolio-lp.git
cd ai-portfolio-lp
open index.html
```

`open` は macOS のコマンドです。Windows は `start index.html`、Linux は `xdg-open index.html`。

## デプロイ

静的HTML1枚なので、[Vercel](https://vercel.com/) にリポジトリを接続すればそのまま公開されます。ビルドコマンドの設定は不要です。

## ファイル構成

```
.
├── index.html   # LP本体
├── CLAUDE.md    # 制作ルール
├── README.md
└── assets/      # 画像などを使う場合に配置
```

## 制作について

企画から公開まで [Claude Code](https://claude.com/claude-code) を使って制作しました。プロフィールの整理 → 設計図づくり → 実装、という順番で進めています。制作ルールは [CLAUDE.md](CLAUDE.md) にまとめています。

## ライセンス

掲載している文章・プロフィール内容の無断転載はご遠慮ください。
