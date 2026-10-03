# Transfer test — NINO / TCSQ

**Date:** 2026-10-03  
**Input candidate:** functional temporal concentration / pressure hinge  
**Result:** mutation confirmed; literal transfer failed where event units differ

## Transfer records

```yaml
- id: CA-20261003-013
  source:
    - /home/shane/Projects/tcsq-quarry/tiles/X01_False_Exit.md
    - /home/shane/Projects/tcsq-quarry/tiles/A12_Return_To_Report.md
    - /home/shane/Projects/tcsq-quarry/tiles/G01_Gap.md
    - /home/shane/Projects/tcsq-quarry/tiles/R01_Reverse_Sentence.md
  kind: skill-candidate
  label: route-pressure concentration
  status: extracted
  description: When chronology is unavailable or not primary, pressure concentrates in route transitions rather than time intervals.
  evidence: false exit routes to altered return; gap routes to report and reverse sentence; punctuation changes motive without changing most words.
  relations:
    - type: mutates-to
      target: functional temporal concentration
      basis: inferred
  delta:
    novelty: Preserves the decision delta while changing the carrier from time sequence to reader route.
    differs_from: literal application of dated-message concentration
  open_questions:
    - Does the route pressure survive a non-game linear reading?
    - Which route transitions are load-bearing and which are merely interface links?

- id: CA-20261003-014
  source: /home/shane/Projects/ninio-mar/book/SPINE.md; /home/shane/Projects/ninio-mar/book/BIBLE.md
  kind: skill-candidate
  label: alternation as function preservation
  status: extracted
  description: NINO declares an alternation of memoir, allegory, fragment, education, and memoir while the Bible protects distinct narrative organs and forbids unsafe clustering.
  evidence: explicit alternation pattern; functional currents; anti-cluster and displacement rules.
  relations:
    - type: supports
      target: pressure-hinge-preservation
      basis: inferred
  delta:
    novelty: The receiving carrier preserves function by alternating narrative organs rather than by fractional numbering.
    differs_from: Like the Sun decimal hinge units
  open_questions:
    - Does each alternation point correspond to a measurable pressure transition?

- id: CA-20261003-015
  source:
    - /home/shane/Projects/tcsq-quarry/tiles/G01_Gap.md
    - /home/shane/Projects/tcsq-quarry/tiles/X01_False_Exit.md
    - /home/shane/Documents/Like the Sun/Like the Sun, From a Distance.md
  location: TCSQ gap/false-exit tiles; Like the Sun Appendix sections “Material que faltaba” and “Manuscript Insertions”
  kind: skill-candidate
  label: omission as route generator
  status: extracted
  description: Missing or withheld material can force a new reading route instead of merely reducing information.
  evidence: TCSQ leaves the gap visible and routes to altered return; Like the Sun surfaces omitted material through an appendix and five insertions that change where the reader re-enters the manuscript.
  relations:
    - type: mutates-to
      target: route-pressure concentration
      basis: inferred
  delta:
    novelty: Extends the gap operator from interactive route movement to manuscript re-entry and structural supplementation.
    differs_from: treating omission as simple incompleteness or editorial defect
  open_questions:
    - Does NINO’s anti-cluster policy use omission in the same route-generating way?
    - What is the minimum visible trace required for an omission to remain functional rather than merely missing?
```

## Transfer verdict

| Candidate | NINO | TCSQ |
|---|---|---|
| Temporal concentration | not comparable yet; no equivalent event log | literal transfer fails; no dated event stream |
| Pressure hinge | mutated into alternation of narrative organs | confirmed as route transition and altered return |
| Preserve function, not artifact | explicit in Bible’s displacement and anti-cluster rules | explicit in G01: preserving shape can destroy use |
| Contradiction routing | explicit anti-verdict and multiple currents | explicit gap, ambiguity, and return routes |

The result is a **functional transfer**, not a shared artifact taxonomy. The
next implementation question is whether the engine should expose one abstract
operator with carrier-specific adapters, or keep separate skills for temporal,
narrative-organ, and route pressure.
