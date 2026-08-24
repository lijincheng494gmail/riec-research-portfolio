# RIEC-L1: critique-to-revision matrix

## Outcome

RIEC-L1 moved from an *evidence-led hybrid selection layer* to an
*evidence-led conflict-resolution layer*. The published contribution is not a
new information criterion or a universally superior selector. It is a
predeclared operation that maps a finite evidence ledger to one reproducible,
conditional recommendation.

## Version chain

| Stage | External challenge | Revision action | Scientific consequence |
|---|---|---|---|
| Initial review, 16 April 2026 | Moderate novelty; incomplete definitions; heuristic schedule and effective-sample-size term; narrow benchmarks; limited uncertainty and comparator evidence | Major revision invited | The initial framing could not survive as a broad model-selection contribution |
| First major-revision package, 5 May 2026 | Needed full operational definitions and direct established-method comparisons | Added grouped risk, XPE, BIC-style quantities, hybrid score and selector; compared AIC, AICc, BIC-style signals, grouped CV and RIEC-L1 | Made the implementation auditable, but did not yet establish a new capability beyond combining familiar evidence |
| Editorial return, 12 May 2026 | Renaming the method a protocol did not solve the novelty problem; the schedule lacked a principled status; the key drying disagreement was statistically inconclusive; `n_eff` sensitivity weakened the calibration story | Revision was returned before re-review | Forced a reconstruction of the scientific object rather than another cosmetic rewrite |
| Editorial-check resubmission, 3 July 2026 | Explain what the layer does beyond side-by-side inspection and retain the negative evidence honestly | Separated evidence ledger from decision map; added score gaps, runner-up margin, pairwise switching condition and `c` switchpoint; stated seven evidence boundaries | Changed the contribution from a weighted hybrid score story to a computable conflict-resolution operation |
| Focused R2, 15 July 2026 | Clarify uncertainty, limited independent groups, schedule stability, terminology, references, repository availability and AI disclosure | Added descriptive group-level error ranges, a compact stability summary, a terminology audit and consolidated limitations | Improved reporting and scope control without changing any benchmark observation, winner, p-value or decision output |
| Acceptance, 16 July 2026 | Final editorial assessment | Accepted and published as *Array* 31 (2026) 101097 | The accepted paper carries a narrower, conditional and reproducibility-centered claim |

## What changed scientifically

### 1. Method identity

The first revision still treated RIEC-L1 as a hybrid score combining a
BIC-style structural signal with grouped predictive risk. The editorial return
made clear that a weighted combination was not, by itself, a sufficient novelty
claim. The later revision therefore defined the added capability as a
predeclared resolution of disagreement: the evidence ledger remains descriptive,
while a declared decision context determines how one conditional recommendation
is produced.

### 2. Mathematical completeness and auditability

The revision supplied the grouped-CV risk, baseline-relative XPE, BIC-style
comparison signal, declared score and selector. The reconstruction then added
candidate-specific gaps, a runner-up conflict margin, a pairwise switching
condition and an explicit `c` switchpoint. These objects made it possible to
audit when and why a recommendation changes.

### 3. Schedule status

The schedule `lambda_n = c / log(n_eff)` was not defended as oracle-derived,
estimated from data or asymptotically optimal. It became a declared
reproducibility setting whose transfer requires a new sensitivity analysis.
The revision reported the observed stability region and used the switchpoint to
show where a pairwise recommendation would change under a fixed evidence
ledger.

### 4. Dependence and effective sample size

Grouped holdout evaluation became the primary safeguard against within-curve
dependence. `n_eff` was restricted to a replaceable penalty-calibration input.
The row-count reduction audit was explicitly not described as a validated
group-count effective-sample-size analysis or a correlated-error likelihood.

### 5. Negative drying evidence

Drying remained the only disagreement regime. The first major revision added
fold-wise errors and paired sign and Wilcoxon checks; those checks were
inconclusive. The later paper preserved that outcome, treated it as weak
evidence, recognized Page and Weibull as equivalent parameterizations of the
same two-parameter class, and avoided claiming superiority over Midilli or
grouped CV.

### 6. Controlled audit versus new evidence

A deterministic residual-anchored intervention path was added to trace the
compact-versus-flexible decision margin. The manuscript explicitly states that
this path is not independent empirical validation, a fourth benchmark or a
stochastic simulation.

### 7. Final scope

Optics and RTD contained only four and three independent deployment groups;
drying contained six held-out conditions. The final paper therefore describes
the cases as methodological demonstrations under declared finite libraries, not
strong external validation or proof of universal predictive dominance.

## Durable lesson

The decisive revision was not the addition of more metrics. It was the change
from claiming that a hybrid score was novel to specifying a transparent
decision operation, its switching behavior, its assumptions and the evidence
that it could not override.
