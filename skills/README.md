# スキルの入口と契約

各スキルが受け取るものと返すものを示す。使う場面と判断手順の正本は、各 `SKILL.md`。
全体をつなぐときは [use-case-design](use-case-design/SKILL.md)、個別の作業には対応するスキルを使う。

| スキル | 受け取るもの | 返すもの |
| --- | --- | --- |
| [problem-framing](problem-framing/SKILL.md) | 困り事、具体例、制約 | 問題、望む成果、今回の範囲、仮説・未確認事項 |
| [domain-modeling](domain-modeling/SKILL.md) | 要求・業務の具体例、既存の用語 | 用語と概念の関係、仮置きのルール、未決事項 |
| [use-case-discovery](use-case-discovery/SKILL.md) | 目的・範囲、具体例、ドメインモデル | アクターの目標に基づく候補、きっかけ・完了結果、境界 |
| [use-case-writing](use-case-writing/SKILL.md) | 選んだ候補、要求、ドメインモデル | 基本・代替コース、根拠・未決事項、必要なら既存の受け入れ条件との対応 |
| [robustness-analysis](robustness-analysis/SKILL.md) | ユースケース、ドメインモデル、関連画面、既知の制約 | ロバストネス図、具体化した本文・モデル、残る確認事項 |
| [use-case-review](use-case-review/SKILL.md) | 要求、ユースケース、モデル、関連画面、予備設計レビューではロバストネス図 | 確認した範囲、不足・矛盾の箇所と影響、修正案・確認事項 |
| [use-case-design](use-case-design/SKILL.md) | 依頼と既存の問題整理・モデル・シナリオ | 必要な工程を通じて整えた成果物と、次へ渡す判断 |
| [design-investment-review](design-investment-review/SKILL.md) | 成果・期限・制約、変更案、便益と負担の根拠 | 推奨する投資範囲、受け入れる負担、再検討条件 |
| [policy-cloud-release-update](policy-cloud-release-update/SKILL.md) | Notionページ、基準日・期間（省略可）、公開状況の補足 | GitHubを根拠に更新した顧客向けリリース・ロードマップ、モック・出典、未確認事項 |

既存の成果物を引き継ぎ、分からないことは未決として渡す。各行のために別ファイルや同じ仕様の写しを作らない。
記述・分析・レビューで概念が変わればモデルへ、解く問題が変われば問題整理へ戻す。
各スキルの出典・補足は、その `SKILL.md` からたどる。
