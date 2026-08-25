# Pre-RIEC Systems retrospective

## Historical status

An infrared-interference thickness-metrology manuscript was submitted to
*Systems* on 13 September 2025 and was subsequently rejected at editorial
screening. The editorial message used general discipline, novelty and
significance criteria; it did not provide a technical diagnosis. The points
below are therefore a later author audit, not claims about the editor's hidden
reasoning.

![Systems portal record](../assets/evidence/systems_editorial_status_2025-09-13.png)

*The portal crop records the 13 September 2025 submission date and the final
status `Rejected by editor`. It does not show the date on which the decision
was issued.*

## What the submission attempted

The manuscript assembled preprocessing, spectral diagnostics, two-beam and
transfer-matrix comparisons, dual-angle thickness estimation, uncertainty
reporting and a quality-code interface into one deterministic workflow. A
supplementary package included interactive tools, workbooks, tables, source
data and screenshots. This was a real execution achievement, but it was not
yet a stable scientific contribution.

## What retrospective audit found

1. **The evidence base was too small for the deployment language.** Four
   competition spectra could demonstrate a calculation, but they could not
   establish transport across wafers, instruments, laboratories or industrial
   conditions without independent reference measurements.
2. **Development and evaluation authority were not separated.** The same
   spectra informed preprocessing, model choice, parameter tuning and final
   interpretation. Agreement between two angles from the same setting was not
   an independent external validation.
3. **Metric semantics were unstable.** The label `XPE` denoted different
   quantities in different artifacts. A pipeline cannot be audited when the
   named object changes across the manuscript and software.
4. **Some numerical objects were internally inconsistent.** The archived
   results included model-selection sign interpretation that conflicted with
   the stated difference convention and point estimates that did not lie
   inside their reported intervals.
5. **Artifact volume was mistaken for evidential authority.** Determinism and
   rerunnability showed that a computation could be repeated; they did not show
   that the scientific claim was calibrated, externally supported or correctly
   bounded.

## Why this record is retained

The submission is not presented as an early RIEC success. It is retained
because it provides a dated counterexample to the idea that access to powerful
AI automatically produces mature research. AI assistance expanded coding,
writing and packaging capacity; it did not automatically supply stable metric
definitions, independent validation, claim discipline or scientific
responsibility.

This lesson later became operational rather than rhetorical: RIEC-L1 narrowed
the decision object; RIEC-BCI separated evaluation worlds; RIEC-Core froze
protocol and claim authority before lockbox access; and RIEC-Agent tracked
shared evidence across adaptive actors.

## Disclosure boundary

The unpublished manuscript and supplementary archive are checksum-registered
but are not redistributed. The supplement contains uncurated historical files
and third-party competition material. Raw decision correspondence and tracking
links are also excluded. This page reports the author's retrospective audit and
does not imply editorial endorsement of any later project.
