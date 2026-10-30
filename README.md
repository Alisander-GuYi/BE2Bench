# BE2Bench
BE$^2$Bench is a Comprehensive and Open-access Benchmark for Knowledge Evaluation of Large Language Models in the Building Energy and Environment Domain
**BE²Bench** is an open-access benchmark dataset for knowledge evaluation of Large Language Models (LLMs) in the **Building Energy and Environment** domain. It contains **1490 questions** selected from a large raw question pool, covering nearly all major knowledge clusters of a million-node building science knowledge graph.

The full dataset is provided as a single Excel file: **[`BE2Bench.xlsx`](BE2Bench.xlsx)**.

> **Status.** This dataset accompanies a manuscript currently under review. The dataset is released now to support open evaluation. 

---

## Dataset

### File

`BE2Bench.xlsx` — one sheet, 1490 rows plus a header row.

### Columns

| Column | Description |
|---|---|
| `Type` | Question type, e.g., `Single choice`, `Cloze` |
| `Topic` | Topic label, e.g., `Air Conditioning & Ventilation`, `Heat Transfer` |
| `Question` | Question text; for single-choice questions, options are listed inline as `A. … B. … C. …` |
| `Answer` | Reference answer together with a step-by-step explanation |
| `KM` | Knowledge Memory score, integer in `{1,2,3,4}` |
| `KU` | Knowledge Understanding score, integer in `{1,2,3,4}` |
| `R`  | Reasoning score, integer in `{1,2,3,4}` |
| `C`  | Calculation score, integer in `{1,2,3,4}` |

The total capability score is the sum of the four dimensions and ranges from 4 to 16.

