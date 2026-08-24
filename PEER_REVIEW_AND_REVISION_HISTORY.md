# Peer-review and revision history

This record explains how external criticism changed the scientific positioning,
implementation and claim boundaries of two early RIEC projects. It is based on
author-held decision letters, reviewer reports and archived submission files.
The correspondence itself is not reproduced because it contains private contact
details and editorial-system links. Reviewer comments are paraphrased rather
than quoted.

This is a development record, not a claim that reviewers endorsed later RIEC
projects or that rejection decisions constitute scientific validation.

## RIEC-L1: revision changed the identity of the contribution

### 16 April 2026 - major revision

The initial *Array* review regarded the engineering problem as useful but the
methodological novelty as moderate. The main objections were that the proposal
looked like a weighted combination of grouped cross-validation and a BIC-style
penalty; the mathematical definitions and implementation details were
incomplete; the schedule based on effective sample size was heuristic; the
three benchmarks were narrow; and statistical uncertainty, sensitivity and
comparisons with established alternatives were limited.

### 12 May 2026 - revision returned for further work before re-review

The first revision was not allowed to proceed merely by renaming the method a
protocol. The editor required a substantive explanation of the capability added
by the decision layer. The revision also had to confront two negative results:
the drying case - the principal disagreement case - was statistically
inconclusive, and stress-test insensitivity to reductions in effective sample
size weakened any strong claim that effective-sample-size calibration was
essential.

### Scientific changes made

The later revision:

- repositioned RIEC-L1 as a deterministic conflict-resolution operation for a
  finite candidate library, not a new risk estimator or universally superior
  information criterion;
- defined the evidence ledger, decision map, XPE, hybrid score, candidate-score
  gaps and switching boundaries explicitly;
- described the schedule as a declared reproducibility choice rather than a
  theoretically optimal rule, and reported schedule sensitivity;
- limited the role of effective sample size to penalty calibration rather than
  treating it as a validated count of independent observations;
- retained the inconclusive drying result and described the paired tests as
  exploratory;
- made the small number of independent deployment groups and the resulting
  uncertainty part of the claim boundary; and
- emphasized the practical value of a predefined, reproducible decision map
  over inconsistent post-hoc interpretation of BIC and grouped-CV rankings.

### 15-16 July 2026 - minor revision and acceptance

After re-review, the remaining requests concerned practical interpretation,
schedule-robustness ranges, group-level uncertainty, repository deposition,
terminology and presentation. The second revision was accepted on 16 July
2026. The final article therefore records a narrower but more defensible
contribution than the initial submission.

## Factory digitalization: substantial revision did not close the evidence gap

### 17 May 2026 - major revision with a low-likelihood warning

The *Results in Engineering* decision identified problems in the statistical
objects, virtual-factory generator, validation design, guard specification,
tail claims, external validity, comparators, reproducibility and engineering
interpretation. The editor explicitly warned that acceptance remained unlikely.

### R1 revision completed

The archived R1 submission shows a material rebuild rather than a cosmetic
rewrite. It:

- defined the confidential manifest, synthetic feature matrix, synthetic
  response, group labels and benchmark-loss scale separately;
- replaced ambiguous validation with business-unit-blocked GroupKFold and
  recorded zero group overlap;
- formalized RIEC-B as a deterministic guard with fixed triggers, a CV-gated
  candidate pool, fallback rules and a decision log;
- replaced the original 50-seed tail claim with primary and stress benchmarks
  of 500 repetitions each, including tail summaries and uncertainty reporting;
- described the virtual factory as a constrained confidentiality-preserving
  benchmark rather than a causal replica of the industrial system;
- added generator diagnostics, a retrospective external-validity bridge, a
  comparison table, an engineering-applications section and a reviewer-safe
  reproducibility package; and
- narrowed the central claim from dramatic tail-risk superiority to a modest,
  auditable and cluster-aware engineering-informatics protocol.

The revised results were also non-oracular: cluster-aware CV had the lowest
mean loss in the primary benchmark, while RIEC-B showed modest upper-tail
improvement relative to the unguarded rule and stronger aggregate behavior only
in the prospectively defined stress benchmark.

### 2 August 2026 - rejection with transfer recommendation

The revised manuscript was rejected by *Results in Engineering* and offered a
transfer route. The remaining objections were not defects that another round of
wording alone could solve. They included insufficient independent industrial
validation; heuristic guard thresholds and stress regimes; limited candidate
models and modern comparators; incomplete component-level ablation; insufficient
decision-oriented outcomes; uncertainty about synthetic-to-industrial transport;
and the need to balance auditability claims against demonstrated predictive
benefit.

The rejected R1 is therefore retained as a negative development result. It
shows that better logging, more simulation and clearer claims cannot substitute
for missing external evidence or establish that every guard component is
necessary.

## Lessons carried forward

These histories produced several durable research practices:

1. Renaming a heuristic combination does not create methodological novelty.
2. Negative and inconclusive results must remain visible and must narrow claims.
3. The independent unit, deployment split and evidence source must be specified
   before model performance is interpreted.
4. A deterministic audit trail can improve reproducibility without proving
   universal statistical superiority.
5. Simulation can test a mechanism under declared conditions, but it cannot by
   itself establish external industrial validity.
6. Component necessity requires targeted ablation or risk activation; it cannot
   be inferred from the completeness of a framework.
7. Some evidence gaps require new data or a narrower claim, not another revision
   of the same analysis.

