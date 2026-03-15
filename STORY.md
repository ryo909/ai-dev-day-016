# Day016 Story — Budget Tradeoff Calculator

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day016専用にテーマをseed固定して再生成時の見た目を安定化
- productivity用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: budget_optimization
- Mechanic: constrained_weighted_formula
- Input/Output: slider_weights_and_rows -> ranked_scores
- Audience Promise: faster_budget_alignment
- Publish Hook: 予算制約下の最適配分を即比較
- Complexity Tier: small
- Selected components: none
- Complexity hint: Keep the tool single-purpose and stable. Add at most one safe enhancement component.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day016｜Budget Tradeoff Calculator
予算配分の妥協点を重み付きで可視化する計算ダッシュボード。（話題:HN Frontpage）
