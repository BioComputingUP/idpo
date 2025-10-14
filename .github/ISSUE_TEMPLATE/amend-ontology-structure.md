---
name: Amend ontology structure
about: Request structural modifications (new parent, merge, split, deprecate/replace)
title: "[REORG] <action>"
labels: ''
assignees: ''

---

**Affected Terms (ID + name)**
(e.g., liquid-liquid phase separation (IDPO:0000025))

**Requested action**
- [ ] update hierarchy
      - Proposed new Parent Term and ID
      - Annotations to be modified (e.g. any definition tweaks needed to fit the new parent)
- [ ] merge
       - “Target” term to keep (ID + label)
       - Which annotations to carry over (synonyms with types, xrefs, usage notes)
- [ ] split
      - Proposed new terms (for each: provisional label, definition, parent(s), key differentiating criterion, initial synonyms)
      - Clear assignment rules (how existing annotations should map to each new term)
- [ ] deprecate & replace
      - Obsolescence reason (out of scope, inaccurate, superseded, duplicate, etc.)
      - Replacement guidance: “replaced_by” (one best match) and/or “consider” (alternatives), with IDs.

**Rationale / use case**
Why is this change needed?

**Evidence / references**
PMIDs/DOIs or community discussions.

**Additional Information**
