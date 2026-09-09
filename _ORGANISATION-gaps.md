# Syllabus vs material — gap audit

Every syllabus line for Modules 1, 2 and 5 checked against the contents of all 25 unique
documents. Legend: **✓ covered** · **◐ partial** (named or used, but not taught as its own
topic) · **✗ missing** (no material at all).

---

## Module 1 — Introduction to OR & Linear Programming

| Syllabus topic | | Material |
|---|---|---|
| Introduction | ✓ | Intro to OR.pptx; OR Introduction.pptx |
| Structure of the Mathematical Model | ✓ | Intro to OR.pptx; OR Introduction.pptx |
| Limitations of Operations Research | ✓ | Intro to OR.pptx |
| LP: Introduction, LPP, Requirements, Mathematical Formulation | ✓ | Linear Prog GM.pptx |
| Graphical method | ✓ | Linear Prog GM.pptx |
| Simplex Method | ✓ | OR - Simplex .pptx; OR - Simplex Method.pptx; OR - Simplex  Example.pptx; SIMPLEX & BIG M …sg.pdf; T13 paper Q2a |
| Penalty Cost Method / Big M-method | ✓ | OR - Big M Method.pptx; SIMPLEX & BIG M …sg.pdf; T13 paper Q2b |
| Two Phase Method | ✓ | OR - Big M Method.pptx; OR - Simplex .pptx |
| **Revised simplex method** | **✗** | **none** |
| Duality | ✓ | OR - Duality.pptx |
| Primal – Dual construction | ✓ | OR - Duality.pptx |
| **Symmetric and Asymmetric Dual** | **✗** | **none** |
| **Weak Duality Theorem** | **✗** | **none** |
| **Complimentary Slackness Theorem** | **✗** | one passing mention inside MODI.pptx; never taught |
| **Main Duality Theorem** | **✗** | strong duality is *demonstrated numerically* in OR - Duality.pptx (primal = dual = 800) but never stated or proved as a theorem |
| Dual Simplex Method | ◐ | not taught as a method; appears only as a sub-step of Gomory's algorithm in OR - IPP.pptx (slides 23–25, θ rule + two tables), and one passing line in OR - Duality.pptx |
| **Sensitivity Analysis** | **✗** | **none** |
| Transportation: formulation, solution | ✓ | Transportation Problem.pptx |
| Unbalanced Transportation problem | ✓ | Transportation Problem.pptx; MODI.pptx |
| NW corner rule, least cost method, VAM | ✓ | Transportation Problem.pptx; Stepping Stone Method.pptx; Transportation Problems.docx; T13 paper Q3 |
| Optimality test: stepping stone method | ✓ | Stepping Stone Method.pptx |
| MODI method | ✓ | MODI.pptx |
| Assignment: Introduction, Formulation, Hungarian Method | ✓ | assignment prob_OR.pptx; Intro to OR.pptx (one worked 5×5 example) |
| Processing of n Jobs Through Two / m Machines | ✓ | Sequencing Problems.pptx |
| Graphical Method of Two Jobs m Machines | ✓ | Sequencing Problems.pptx |
| **Routing Problem** | **✗** | named on one recap slide of assignment prob_OR.pptx; never taught |
| Travelling Salesman Problem | ✓ | TSP.pptx |
| IPP: Introduction, Types | ✓ | OR - IPP.pptx |
| Gomory's cutting plane Algorithm | ✓ | OR - IPP.pptx (steps + full worked example, slides 6–26) |
| Branch and Bound Technique | ✓ | OR - IPP.pptx (slides 27–46, worked example) |
| **Introduction to Decomposition algorithms** | **✗** | **none** |

## Module 2 — Queuing Models

| Syllabus topic | | Material |
|---|---|---|
| Queuing systems and structures | ✓ | Queuing PPT.pdf |
| Single server models | ✓ | Queuing PPT.pdf — full formula set (Ls, Lq, Ws, Wq, Lq′, P(n), utilisation & idle rate) + 3 worked examples |
| Multi-server models | ◐ | listed as a heading on the models slide, but **no multi-server formulas and no multi-server example** — every formula and all three examples are single-server |
| Poisson input | ✓ | Queuing PPT.pdf |
| Exponential service | ✓ | Queuing PPT.pdf |
| Constant rate service | ◐ | one line only: "Constant Service Time : Not in practice" — no model, no formula |
| Finite and infinite population | ✓ | Queuing PPT.pdf (calling population, infinite queue scenarios) |

## Module 5 — Game Theory

| Syllabus topic | | Material |
|---|---|---|
| Competitive games | ✓ | Game Theory.pptx |
| Rectangular game | ✓ | Game Theory.pptx; Game Theory_1.pptx |
| Saddle point | ✓ | Game Theory.pptx; Game Theory_1.pptx; example_1.pptx |
| Minimax (maximin) method of optimal strategies | ✓ | Game Theory.pptx; Game Theory_1.pptx |
| Value of the game | ✓ | Game Theory.pptx; Game Theory_1.pptx |
| Solution of games with saddle points | ✓ | Game Theory_1.pptx (8 solved/set problems) |
| Dominance principle | ✓ | Game Theory.pptx; Game Theory_1.pptx; example_1.pptx |
| Rectangular games without saddle point — mixed strategy for 2×2 | ✓ | Game Theory.pptx; Game Theory_1.pptx (6 solved + 4 set with answers) |

**Module 5 is completely covered — no material is missing.**

---

## Summary of gaps

**Missing outright (8), all in Module 1:**

1. Revised simplex method
2. Symmetric and Asymmetric Dual
3. Weak Duality Theorem
4. Complimentary Slackness Theorem
5. Main Duality Theorem *(demonstrated numerically, never stated as a theorem)*
6. Sensitivity Analysis
7. Routing Problem
8. Introduction to Decomposition algorithms

**Partially covered (3):**

- Dual Simplex Method (Module 1) — only as a sub-step of Gomory's algorithm
- Multi-server queuing models (Module 2) — heading only, no formulas or example
- Constant rate service (Module 2) — one dismissive line

**Also absent:** a **previous-year MSE paper**. `or_imporatnt _questions.docx` explicitly
points to one ("For the numericals mse previous year mse questions") but no such paper is in
the folder. The past **Internal Assessment I** paper that *is* present is a different
assessment — 20 marks in 1 hour, against the MSE's 30 marks in 1.5 hours.

Modules 3 (Simulation), 4 (Dynamic Programming) and 6 (Inventory Models) are outside the
stated MSE scope and have no material in the folder either.
