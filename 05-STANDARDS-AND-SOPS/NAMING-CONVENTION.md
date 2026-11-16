# Naming Convention

## Company and asset identifiers

| Asset | Pattern / starting example |
|---|---|
| Company | `AIE` |
| Character | `AIE-CHR-001` |
| Content | `AIE-CNT-0001` |
| Campaign | `AIE-CMP-001` |
| Product | `AIE-PRD-001` |
| Experiment | `AIE-EXP-001` |

These are identifier patterns and examples, not evidence that assets exist. Allocate identifiers sequentially in a register when approved assets are created; do not reuse retired identifiers.

## Files and dates

Core filenames use uppercase English words separated by hyphens, with `.md` for Markdown. Dates use ISO `YYYY-MM-DD`. Avoid personal names or confidential data in filenames. Add a dated suffix only when multiple distinct records of the same type are needed.

## Document versions

Use Git history for version tracking. Include a document status and last-reviewed date where operationally useful. Record material changes in the change log; do not introduce a separate release platform or claim semantic versions for documents without need.
