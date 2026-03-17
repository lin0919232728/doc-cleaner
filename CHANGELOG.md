# CHANGELOG — doc-cleaner01

## 2026-03-14 17:43 v1.0.3 (DOCX/XLSX 修復 + Groq 支援)

- fix: DOCX header heuristic — 改善標題偵測準確度
- fix: XLSX wide table truncation — 寬表格不再被截斷
- feat: add Groq backend support — 新增 Groq LLM 後端選項
- code cleanup
- Git: `fe2353b`, `f060425`

## 2026-03-14 09:53 v1.0.2 (PII Redaction + 專家審查修復)

- feat: add opt-in PII redaction for Taiwan personal data（台灣個資遮罩）
- fix: address 10 issues from expert code review
- Git: `f8ba941`, `eebca81`

## 2026-03-11 08:37 v1.0.1 (Code Review 修復 + 安全強化)

- fix: resolve multiple bugs found in code review
- fix(security): harden P2–P4 issues from hacker audit
- Git: `ce29a5a`, `1b635ce`

## 2026-03-10 00:56 v1.0.0 (初版)

- feat: PDF/DOCX/XLSX/TXT to structured Markdown converter
- Git: `30c9b4e`
