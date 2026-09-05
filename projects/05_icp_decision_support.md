# ICP — Standalone Owner Tool / Public-safe Decision Support

## 解いた問題

Primary GoalはOwner本人が日常利用するStandalone Toolです。Public版はPrivate情報を除いた固定Projectionです。

## 実データ

公開初版: **2026-08-27 Reviewed Slice**

| Collector | evaluated | saved |
|---|---:|---:|
| Global | 8 | 0 |
| CV | 10 | 1 |
| AI | 16 | 1 |
| Historical | 8 | 3 |

合計 **42 evaluated / 5 saved / 3 Decision Themes**。

## Data Quality

- 42はCorpus全量ではありません。
- Full-window denominator: `UNKNOWN`
- Cross-collector exact unique: `NOT_COMPARABLE`
- Live / Current / Today's ICPではありません。

## Selection Trace

`42 evaluated → 5 saved → 3 Decision Themes` は `public_snapshot.json` から再生成します。

## 3 Decision Cases

### Case 1: AI Security / Sensitive Action Pattern

**ICP Decision Support:** Design Pattern Candidate。正式採用済みではありません。

- Evidence: PUBLIC_EVIDENCE_DETAIL_NOT_PROVIDED_IN_APPROVED_HANDOFF
- Counterevidence: PUBLIC_COUNTEREVIDENCE_DETAIL_NOT_PROVIDED_IN_APPROVED_HANDOFF
- Unknown: Evidence detail: NOT_PUBLISHED_IN_APPROVED_HANDOFF
- Next Evidence: UNSTRUCTURED_IN_APPROVED_HANDOFF
- Change Condition: UNSTRUCTURED_IN_APPROVED_HANDOFF

### Case 2: Warehouse Autonomous Drone

**ICP Decision Support:** 全面導入推奨ではなく、条件一致時のPoC Candidate。

- Evidence: PUBLIC_EVIDENCE_DETAIL_NOT_PROVIDED_IN_APPROVED_HANDOFF
- Counterevidence: PUBLIC_COUNTEREVIDENCE_DETAIL_NOT_PROVIDED_IN_APPROVED_HANDOFF
- Unknown: Evidence detail: NOT_PUBLISHED_IN_APPROVED_HANDOFF
- Next Evidence: UNSTRUCTURED_IN_APPROVED_HANDOFF
- Change Condition: UNSTRUCTURED_IN_APPROVED_HANDOFF

### Case 3: Autonomous Lab / AI Research Evaluation

**ICP Decision Support:** Experiment Countだけを成功指標にせず、Closed-loop Improvement / Objective Quality / Physical Executability / Downstream Outcome / Human Intervention / Cross-system Reproducibilityを優先。Broadな未来断定はしません。

- Evidence: PUBLIC_EVIDENCE_DETAIL_NOT_PROVIDED_IN_APPROVED_HANDOFF
- Counterevidence: PUBLIC_COUNTEREVIDENCE_DETAIL_NOT_PROVIDED_IN_APPROVED_HANDOFF
- Unknown: Evidence detail: NOT_PUBLISHED_IN_APPROVED_HANDOFF
- Next Evidence: UNSTRUCTURED_IN_APPROVED_HANDOFF
- Change Condition: UNSTRUCTURED_IN_APPROVED_HANDOFF

## Reproducibility / Public Safety

Private Source → local staging → Public-safe projection → validation → leak scan → hash固定 → `PUBLIC_EXPORT_READY`。Missingを推測補完しません。

## Owner / AI役割分離

ICP Decision SupportとOwner Final Decisionを分離し、MachineはOwner Final Decisionを生成しません。

## Standalone Tool

Windows 1操作でLocal RepositoryをRead-only確認し、Remoteとの差分・freshness失敗を明示します。

## Public Demo

[Static Demo](../demos/icp/index.html)
