# Experimental-operator sweep reset

**Date:** 2026-10-03  
**Plugins:** Shane Cognitive Mesh & Frontier Engine + Shane Experimental Operators  
**Mode:** discovery reset; capture before organization

## New observation

```yaml
- id: CA-20261003-012
  source:
    - /home/shane/Documents/Like the Sun/Analisis_de_concentracion_de_eventos B.md
    - /home/shane/Documents/Like the Sun/Inventario_eventos_concentracion.csv
  location: concentration analysis, result, concentration-within-concentration, sequence
  kind: skill-candidate
  label: functional temporal concentration
  status: extracted
  description: Group consecutive messages by observable function, then measure where grouped operations cluster in time and whether intervals shorten while functions mutate.
  evidence: 21 grouped operations; 16 in the final tenth; 14 of those in approximately fifty hours; the analysis preserves functions such as concealment, inversion, counteraccusation, admission, self-condemnation, silence, closure, and contact prohibition.
  relations:
    - type: observed-in
      target: Like the Sun support corpus
      basis: direct
    - type: supports
      target: fractional chapter as pressure hinge
      basis: inferred
  delta:
    novelty: Replaces message-count narrative with function-grouped temporal density and cascade detection.
    differs_from: treating each message as an independent event or treating the ending as uniformly conflictual
  open_questions:
    - Does the grouping rule reproduce on an independent corpus without changing the unit definition?
    - Which threshold distinguishes a meaningful cascade from ordinary high-volume communication?
    - Can this detect literary pressure without importing clinical claims?
```

## Operator contract under test

```yaml
input: dated messages or scenes with a declared source boundary
capture: preserve raw events and competing labels before grouping
operation:
  - group adjacent units only when they share one observable function
  - record the grouping rule and excluded events
  - measure density by time window
  - detect shortening intervals and function mutation
output: concentration map plus unresolved causal alternatives
failure:
  - counting volume as meaning
  - treating retrospective labels as contemporaneous facts
  - turning density into diagnosis
  - collapsing contradiction into one motive
```

## Contradiction routing

The analysis supports two locally valid readings that must remain separate:

1. **Descriptive route:** a documented cascade of operations becomes denser,
   changes function, and produces observable consequences.
2. **Clinical/inferential route:** the same convergence may be compatible with a
   mixed episode, but the corpus cannot establish a retrospective diagnosis.

The first route is source-grounded. The second remains an inference and cannot
replace the first. They are not averaged.

## Selection receipt

- **Preserved:** raw-event boundary, grouped-operation rule, excluded coda,
  density figures, competing explanations, uncertainty about causation.
- **Not selected:** retrospective diagnosis as a literary or operational fact.
- **Authority:** source-first extraction; no production or canon decision made.
- **Reversible:** later raw-source review may split, merge, or reject groups.

## Transfer queue

Apply the operator next to NINO and TCS/TCSQ only after defining their event
unit. A structural chapter sequence is not automatically comparable to a dated
message sequence; that mismatch must be recorded rather than repaired.
