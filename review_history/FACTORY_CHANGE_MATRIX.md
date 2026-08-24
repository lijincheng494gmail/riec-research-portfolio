# Factory digitalization: critique-to-revision matrix

## Outcome

The Factory manuscript received a major-revision decision, underwent a material
R1 rebuild, and was rejected by *Results in Engineering* on 2 August 2026 with
a transfer recommendation. The revision improved auditability and corrected
several design problems, but it did not create the independent industrial
evidence, threshold theory or component-level necessity evidence required for
the stronger claim.

## Critique-to-revision map

| Challenge | R1 action | What the action established | What remained unresolved |
|---|---|---|---|
| Statistical objects and provenance were unclear | Defined the confidential manifest, synthetic feature matrix, synthetic response, group labels and benchmark-loss scale separately | The data roles and evidence provenance became auditable | Definitions could not turn synthetic evidence into independent industrial validation |
| Validation risked mismatch or leakage | Replaced ambiguous validation with business-unit-blocked GroupKFold and recorded zero train-validation group overlap | The benchmark estimated transfer across declared operational groups rather than random rows | The limited confidential setting still constrained generalizability |
| The guard was insufficiently specified | Formalized RIEC-B with fixed triggers, a CV-gated candidate pool, fallback behavior and a decision log | The guard became deterministic and reproducible | The threshold choices remained heuristic and component necessity was not established |
| Tail claims relied on too few repetitions | Replaced the 50-seed analysis with primary and stress benchmarks of 500 repetitions each; reported mean, median, q95, q99, maximum and bootstrap tail intervals | Tail behavior was characterized more credibly and negative/mixed results became visible | More simulation did not prove external benefit or universal tail superiority |
| The virtual factory risked being interpreted as a causal industrial replica | Reframed it as a constrained, confidentiality-preserving benchmark and added generator diagnostics | The manuscript stopped claiming that the synthetic environment reproduced the full causal factory | Synthetic-to-industrial transport remained uncertain |
| External validity was weak | Added a retrospective bridge to the limited real-data context | Provided a bounded consistency check | It was not a prospective independent industrial validation |
| Comparators and engineering interpretation were limited | Added a comparison table, engineering-applications section and clearer baseline positioning | Made the practical decision context and comparator behavior easier to inspect | Modern comparator breadth, decision-oriented outcomes and multi-industry evidence remained limited |
| Reproducibility was incomplete | Added a reviewer-safe reproducibility package and preserved decision logs and benchmark outputs | The revised computation became inspectable | Reproducibility could not substitute for missing external evidence |

## R1 numerical interpretation

The primary 500-repetition benchmark did not show universal RIEC-B dominance.
Cluster-aware CV achieved the lowest mean loss (`1.420`). Relative to the
unguarded rule, RIEC-B showed modest upper-tail changes (`q95` `1.943` versus
`1.979`; `q99` `2.152` versus `2.214`). When the guard fired, RIEC-B improved
the result in 328 of 445 cases, with an average loss reduction of `0.238`.

In the prospectively defined stress benchmark, RIEC-B had aggregate mean loss
`2.663`, `q95` `4.042`, and a guard-trigger rate of `92.9%`. It was not the
universal `q99` winner. The revision accordingly narrowed the claim from
dramatic tail-risk superiority to a modest, auditable and cluster-aware
engineering-informatics protocol.

## Why the revision still ended in rejection

The remaining objections required either new evidence or a smaller scientific
claim. They included:

- independent external industrial validation;
- principled threshold justification and broader threshold sensitivity;
- stronger modern comparators and decision-relevant outcomes;
- targeted component ablation or risk activation;
- clearer transport from synthetic mechanisms to industrial benefit;
- additional cluster and uncertainty analysis; and
- evidence beyond one finite candidate library and one industrial setting.

The rejected R1 is retained as a negative development result. It demonstrates
that extensive simulation, documentation and provenance can improve the
quality of an analysis while remaining insufficient to support a broad claim of
predictive or external industrial benefit.
