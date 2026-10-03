# Support-material extraction ledger

Initialized from the low-resolution inventory. This is a ledger, not a conclusion. Each observation must retain source path, location, bounded evidence, object type, confidence, relations, delta, and open questions.

## Seed records

```yaml
- id: CA-20261003-001
  source: /home/shane/Documents/Like the Sun/
  location: root inventory
  kind: negative-space
  label: support corpus is larger than recovered book surfaces
  status: observed
  evidence: 332 files inventoried; assignment not inferred from filenames
  open_questions:
    - Which files contain stories not represented in the current repositories?

- id: CA-20261003-002
  source: /home/shane/Documents/Like the Sun/
  location: Como_el_sol_desde_la_distancia_Manuscrito_*.docx and Like the Sun, From a Distance.md
  kind: hypothesis
  label: Like the Sun version family
  status: extracted
  evidence: three DOCX versions plus one Markdown title match
  open_questions:
    - Are these chronological revisions, alternate exports, or different assemblies?

- id: CA-20261003-003
  source: /home/shane/Documents/Like the Sun/
  location: Las sillas*.docx and Las sillas que no hacen sombra.docx
  kind: hypothesis
  label: chair-piece family
  status: extracted
  evidence: multiple chair-titled files, including a duplicate-marked filename
  open_questions:
    - Which is source, which is revision, and how does the family relate to Don Xavier?
```

## Capture rule

Do not add a mechanism merely because a title sounds related. Read the source, anchor the observation, and keep story, rule, process record, and archive material in separate records. Duplicates remain separate until comparison is complete.

## First source observations — 2026-10-03

```yaml
- id: CA-20261003-004
  source: /home/shane/Documents/Like the Sun/Like the Sun, From a Distance.md
  location: macro structure, chapter breakdown, appendix, practical keys
  kind: artifact
  label: recovery map is also a transformation manual
  status: observed
  description: The file contains a proposed narrative order, a behavioral map, practical rules, and explicit manuscript insertions in one surface.
  evidence: Acts I-III; chapters 1-12; appendix sections; insertions 1-5.
  open_questions:
    - Which sections belong to the manuscript and which are editorial scaffolding?
    - Do the insertions occur in v0.2 or v0.3, or only in this support map?

- id: CA-20261003-005
  source: /home/shane/Documents/Like the Sun/Como_el_sol_desde_la_distancia_Manuscrito_v0.1.docx; v0.2.docx; grande_v0.3.docx
  location: document headers and opening paragraphs
  kind: contradiction
  label: version family changes its organizing frame
  status: observed
  description: v0.1 presents a private documentary work manuscript; v0.2 opens with a sectioned literary assembly; v0.3 opens with a compressed literary assembly.
  evidence: v0.1: “Versión 0.1” and working-note/privacy framing; v0.2: “I. Lo dulce todavía respiraba”; v0.3: “I. Lo dulce respiraba”.
  open_questions:
    - What was removed between v0.2 and v0.3?
    - Is the compression a correction, a change of audience, or a different book surface?

- id: CA-20261003-006
  source: /home/shane/Projects/pre-like-the-sun/Quarry/Las sillas que no hacen sombra.md
  location: opening through closing image
  kind: operator
  label: function without shadow
  status: extracted
  description: A large object is evaluated by the secondary space and pressure it creates, not only by its physical size or beauty.
  evidence: The chairs are large but visually light; the text contrasts space with hiding place and preserves a child’s mark over perfect furniture.
  open_questions:
    - Does the same function/shadow opposition recur in Like the Sun or NINO material?

- id: CA-20261003-007
  source: /home/shane/Documents/Like the Sun/El niño que vino del mar - Extended.md; /home/shane/Projects/ninio-mar/book/BIBLE.md
  location: full short narrative; BIBLE canon overrides and functional frame
  kind: contradiction
  label: origin and frame are unstable across support and working repository
  status: observed
  description: The extended support text uses a Pacific-origin, romanticized brother-sister frame; the repository Bible explicitly rejects Pacific origin and defines a broader genealogical, multigenerational frame.
  evidence: Support text says “Pacific”; BIBLE says “Do not use Pacific as origin” and keeps “vino del mar” broad.
  open_questions:
    - When and why was the Pacific origin rejected?
    - Which motifs survive after the romanticized frame is removed?
```
