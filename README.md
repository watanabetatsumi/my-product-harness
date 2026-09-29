# my-product-harness

本・記事から得た知見を、仕様設計や実装の判断に使う個人ハーネス。

| 場所 | 内容 |
| --- | --- |
| `references/books/` | Kindleの引用と、出典・確認範囲を添えた読書メモ |
| `references/articles/` | 記事の出典、要点、考察 |
| [skills/](skills/README.md) | 作業に使うスキルと、その入出力・接続先 |
| [relations.md](relations.md) | 関係ラベルの名前・意味・向きの定義 |

## 知見を残す

本・記事のメモには出典と必要な要点・考察を書く。引用、著者の主張、自分の適用案を区別する。
繰り返し使う判断は `skills/<name>/SKILL.md` に置き、出典のノートへリンクする。
スキルの実行に必要な指示はそのフォルダ内で完結させる。必要時だけ読む補足は、そのスキルの `references/` に置く。
例: [技術「負債」ではなく、借り入れ？](references/articles/技術”負債”ではなく、借り入れ？.md) → [設計と改善への投資判断](skills/design-investment-review/SKILL.md)。

関連する文書をMarkdownリンクやWikilinkでつなぐ。関係の意味を明示する場合は [relations.md](relations.md) のラベルを使う。
同名の `SKILL.md` はパス付きで指定する。例: `[記述](skills/use-case-writing/SKILL.md)`。

## 開き方

FoamはVS Codeでこのリポジトリを開く。推奨拡張と設定は `.vscode/` にある。
現在のObsidian保管庫は `references/books/`。保管庫外のスキルには外部ファイルリンクで接続している。
同じMarkdownを編集する。画面配置・プラグイン設定などの `.obsidian/` はGit管理から除外する。
