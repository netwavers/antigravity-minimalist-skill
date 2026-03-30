# Skill: Minimalist Logic & Resource Control (MACF)

## 1. 思考とリソースの憲法 (Token Economy)
* **1-Shot 完結の原則**
* **推論 Tiering**
* **冗長性の排除**

## 2. 実行の停止条件 (Termination Gates)
* **Zero-Retry Policy**: エラー時にリトライせず停止せよ。
* **Step Limit**: ステップ上限を遵守せよ。

## 3. 実装前の「設計承認」プロトコル (Draft-First)
* **Draft-Only**: 実装前に構成案を提示し、承認を待て。

## 4. 差分（Diff）の最小化 (Diff-Only)
* **Partial Overwrite**: 修正が必要な箇所のみを提案せよ。