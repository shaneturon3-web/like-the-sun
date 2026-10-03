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
