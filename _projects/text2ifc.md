---
layout: page
title: Text2IFC / IFC Repair
description: Language-driven structured 3D model generation and controlled repair.
permalink: /projects/text2ifc/
importance: 1
category: agent
---

**Repository:** [770122whrt/text2IFC](https://github.com/770122whrt/text2IFC)

This research and engineering project studies how to convert natural-language building requirements into structured, verifiable IFC artifacts, and how to apply **controlled local edits** to existing IFC models.

The public repository documents three connected workflows:

1. **Generation:** Requirements and clarification → structured design brief → BIM representation → IFC artifact → validation and audit.
2. **Repair:** An existing IFC model and an instruction → parsing/clarification → explicit **ChangeSet** → copy-based application → multi-layer checks (L0/L1/L2) and conservation checks.
3. **IFC2Text round trip:** IFC facts → design description → the common generation process → independent comparison.

### Engineering focus

- Separate language-model proposals from deterministic validation and artifact operations.
- Express local changes in a form that can be inspected before and after execution.
- Use evaluation gates and comparisons rather than treating model-generated output as proof of correctness.

The project is evolving; supported operations and evaluation outcomes should be judged from the [repository's current documentation](https://github.com/770122whrt/text2IFC), not inferred from this summary.
