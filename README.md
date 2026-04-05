
# AI開発Skill一覧 & TODO管理（更新版）

## Skill一覧（概要）

| Skill名 | 役割 | 入力 | 出力 | 目的 |
|--------|------|------|------|------|
| Requirement → Design | 要件を設計に落とす | 要件 | 設計 | 仕様の構造化 |
| Design → Task Breakdown | 設計をタスク化 | 設計 | タスク一覧 | 実装単位に分解 |
| Task → Implementation Plan | 実装方針決定 | タスク + コード | 実装計画 | 変更箇所明確化 |
| Plan → Code Generation | コード生成 | 実装計画 | 実装コード | 実装自動化 |
| Code → Self Review | 品質チェック | コード | 問題点 | バグ検出 |
| Code → Missing Case Detection | 想定漏れ検出 | コード | 不足ケース | 網羅性向上 |
| Diff → Regression Risk Check | デグレ検出 | diff | リスク | 既存保護 |
| Code → Test Skeleton | テスト雛形生成 | コード | テストコード | テスト高速化 |
| Code → Performance Risk Check | 性能リスク検出 | コード | リスク | 性能事故防止 |
| Change Request → Impact Analysis | 変更影響分析 | 要件変更 | 影響範囲 | 事故防止 |
| Diff → Release Readiness Check | リリース安全性確認 | diff | リスク | 安全なリリース |
| API → Contract Check | 互換性チェック | API変更 | 影響 | 破壊防止 |
| PR → Review | PRレビュー | diff | 指摘 | 品質向上 |
| PR → Review Comment Draft | コメント生成 | review結果 | コメント | 実用化 |
| PR → Approval Readiness Check | 承認判断 | PR | 判定 | マージ判断 |

---

## 実装TODO一覧（未実装のみ）

| Skill名 | 優先度 | 備考 |
|--------|------|------|
| Code → Observability Check | 高 | ログ・監視 |
| Code → Security Check | 高 | セキュリティ |
| Spec / Code → Documentation Sync Check | 高 | ドキュメント整合性 |
| Code → Refactoring Plan | 中 | 可読性改善 |
| Release → Post Release Validation | 中 | リリース後検証 |
| DB → Data Integrity Check | 中 | データ整合性 |
| Code → Dependency Check | 低 | 依存関係整理 |
| Code → Cleanup Detection | 低 | 不要コード検出 |

---

## メモ

- TODOは未実装のみ管理
- 優先度は実務インパクトベース

