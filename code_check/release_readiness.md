
# Diff → Release Readiness Check Skill（AI-Optimized）

## 概要
変更差分をもとに、安全にリリース可能かを判断する skill。

## 目的
- リリース事故防止
- デプロイ戦略明確化

## 入力
- diff
- 実装内容

## 出力
- リリース可否判断
- リスク
- 必要対応

## 観点
- feature flag必要か
- migration順序安全か
- rollback可能か
- 監視必要か

## 本質
「動くか」ではなく「安全に出せるか」を判断する
