# OR-SH2026 — how this folder is organised

Course **OEC7015 Operations Research**. Material was sorted by **reading the contents of every
file**, not by its filename. Three module folders correspond to the three modules in the
stated MSE scope (Modules 1, 2 and 5 of the six-module syllabus).

| Folder | Files |
|---|---|
| `Module 1 - Introduction to OR & Linear Programming` | 19 |
| `Module 2 - Queuing Models` | 1 |
| `Module 5 - Game Theory` | 3 |
| `_Syllabus` | 2 (not module material — the organising reference) |
| `_Duplicate copies` | 19 (identical extras, kept rather than deleted) |

---

## Documents whose filename does not reveal their module

These were placed on content alone:

- **`example_1.pptx` → Module 5.** The name says nothing. It contains a saddle-point worked
  example (4×4 payoff matrix, V = 12) and a dominance-method example with the reduction rules.
  Pure Game Theory.
- **`T13_IA_QP_3CO_solution.docx` → Module 1.** The name is a paper code. It is a past
  **Internal Assessment I** paper *with full solutions and marking rubrics*.
- **`or_imporatnt _questions.docx` → Module 1.** A list of likely 2-mark questions.
- **`SIMPLEX & BIG M ADDITIONAL PROBLEM sg.pdf` → Module 1.** A scan of handwritten notes;
  it extracts as only 152 characters of text, so it had to be read as images. Two fully
  worked problems, and the only source in the folder that uses the **Zⱼ − Cⱼ** convention.
- **`MODI.pptx` → Module 1.** "MODI" is the u-v method for the transportation problem.
- **`TSP.pptx` → Module 1.** Travelling Salesman, listed under Assignment Problem in Module 1
  — not a separate module.

---

## ⚑ FLAGGED — documents that span more than one module

Neither is duplicated. Each sits in the module holding the majority of its content.

### 1. `Module 1/T13_IA_QP_3CO_solution.docx`
A past **Internal Assessment I** paper (Sem VII, Information Technology, Subject: OR,
1 hour, 20 marks) with solutions and rubrics. Split:

| Question | Topic | Module | Marks |
|---|---|---|---|
| Q1 a, b, c | OR advantages; feasible vs optimal; objective function vs constraint | **1** | 2 each (attempt any two) |
| Q1 d, e, f, g | Strictly determinable game; dominance; 2×2 game; fair game | **5** | 2 each (attempt any three) |
| Q2 a, b | Simplex; Big M | **1** | 5 (attempt any one) |
| Q3 a, b | Transportation — VAM; Least Cost; degeneracy | **1** | 5 (attempt any one) |

**Module 1 carries up to 14 of the 20 marks, Module 5 up to 6** → filed under Module 1.
Anyone revising Module 5 should still open this file for Q1 d–g.

*Caveats found while verifying it:* three answers contradict themselves — Q2(b) states "the
solution is unbounded" and then gives `F* = 3.4, X* = (0.4, 1.8)`; Q3(a) gives both 1525 and
1510 as the total cost; Q3(b) says "the solution is degenerate" and then "∴ this solution is
non-degenerate". Independent recomputation: **Q2(b) is bounded and F* = 3.4 at (0.4, 1.8) is
correct — the "unbounded" conclusion is wrong.** Q2(a) (Z = 21 at x₁ = 3, x₂ = 1.5) and
Q1(e) (V = 27/4) both check out exactly. Note also that this paper's CO numbering differs
from the syllabus in `_Syllabus/` (it maps transportation to CO-2; the syllabus maps it to CO-3).

### 2. `Module 1/or_imporatnt _questions.docx`
Eleven 2-mark questions. Ten are Module 1 (OR model, objective function vs constraints,
feasible vs optimal, types of constraints, limitations, transportation, managerial use).
**One is Module 5** — *"Analyze if the following game is strictly determinable, find the
value of the game."* Filed under Module 1; check it when revising Module 5 too.
It closes with the note *"For the numericals mse previous year mse questions"*, which points
at a previous-year MSE paper that is **not present in this folder**.

---

## `_Duplicate copies` — safe to delete, nothing unique inside

18 of the 19 are **byte-identical** to a file kept in a module folder (verified by MD5).
The nineteenth, `Game Theory (recompressed - identical text).pptx`, is not byte-identical but
its extracted text matches the kept copy line for line; it is the same deck re-saved with
lower-resolution images. The **larger, higher-resolution copy was kept in Module 5**, because
every payoff matrix in that deck is an embedded image that has to be read rather than parsed.

---

## Syllabus coverage — see `_ORGANISATION-gaps.md` for the full audit
