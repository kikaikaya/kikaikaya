# 機械化屋（kikaikaya）

レガシーシステムのモダナイゼーション × 生成AI。

AI エージェントでレガシーシステムの調査・マイグレーション評価を自動化する道具を作り、
作る過程ごと公開しています。

## 📦 作っているもの

| プロジェクト | なにか |
|--------------|--------|
| [flowsmith](https://github.com/kikaikaya/flowsmith) | AI エージェントの多段ワークフローを 1 つの YAML で宣言し、中断しても続きから動かすエンジン |
| [migration-factory](https://github.com/kikaikaya/migration-factory) | レガシー現状調査の自動化ワークフロー。実際の調査出力（CSV 17 本 + 報告書 + 実行証跡）を [examples](https://github.com/kikaikaya/migration-factory/tree/main/examples/jpetstore) で公開 |

## ✍️ 書いたもの

- [AIエージェントの多段ワークフローを「1つのYAML」で宣言的に動かす — flowsmith の設計](https://zenn.dev/kikaikaya/articles/flowsmith-declarative-ai-workflow)
- [中断しても続きから動く — AIワークフローのチェックポイント設計](https://zenn.dev/kikaikaya/articles/flowsmith-checkpoint-resume)

## 🔧 領域

レガシーマイグレーション（現状調査 / Oracle → PostgreSQL）・Java・グラフ DB・Claude Code

---

*発信は個人の見解です。*
