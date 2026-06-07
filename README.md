# Accretive Rigor (AR)

## Definition

Accretive Rigor is an operational philosophy and data-governance methodology in
which precision is dynamic and cumulative. It pairs deliberate procedural
discipline with a systematic mechanism for gradual accumulation. Under this
model, execution is not static: the system's structural intelligence, its
recipes and foundational memories, compounds and layers over time with every
interaction.

The name compresses its own definition. Accretion is the compounding accrual of
durable knowledge assets; Rigor is strict precision applied to evidence and
method. A reader who sees only the name can reconstruct the gist: precision that
is not static, but compounds and layers over time.

## Core rationales

### 1. Two-halves alignment (eliminating synonym redundancy)

Earlier naming attempts collapsed into synonym redundancy (for example
"Accretive Compounding", where both words mean accumulation) or favored
execution-only mechanics (for example "Determinative Execution", which names
only the doing). Accretive Rigor documents both halves of the working
methodology in two distinct, non-overlapping terms:

- The Accretion: the compounding accrual of persistent, durable knowledge assets.
- The Rigor: strict precision applied during execution, directed at evidence and
  method.

### 2. Rigor governs evidence, not obedience

The Rigor is a standard for precision and verification, not a mandate to fix the
path and never deviate. It is an objective engineering standard rather than a
subjective feeling like "careful", and it directs that hard standard at evidence
and method:

- Read the relevant rubric, template, or guide before authoring, not after.
- Verify on disk (and by re-checking) before declaring a task complete; prefer
  multiple independent checks over a single assertion.
- Use precise, neutral language; diagnose a tool anomaly before labeling the
  tool, since the cause is often one's own usage error.

Crucially, this rigor applies to correctness, not to restricting choices. It does
not override the preference for guidance over hard rules.

### 3. Deliberation is part of the method

Accretive Rigor includes open deliberation as a first-class half, not an
exception to it. Precision in execution is paired with openness in deciding:

- Prefer guidance, defaults, and "prefer / default to / unless" phrasing over
  absolute prohibitions, which tend to be too restrictive and can open silent
  failure paths that cascade across later choices.
- Keep clarifying questions welcome. Trusting a settled decision means not
  re-litigating it, not suppressing genuine questions about real ambiguity,
  misalignment, or something new.
- Brainstorm and discuss to converge before committing. The determination
  applies after alignment, not before it.

In short: deliberate openly to converge, then execute with rigor on what is
settled, and deposit the verified result as a compounding asset.

### 4. Scale invariance

"Accretive" operates across architectural layers at once:

- Local scale: a single session deposits durable assets (versioned recipes and
  session memories) that immediately enrich the next run.
- Global scale: a shared store of recipes and memories grows in systemic value
  over its whole lifecycle, each deposit raising the floor every future session
  starts from.

### 5. Knowledge as a living data layer (non-codebase mapping)

Traditional technical frameworks lean on execution variables, unit tests, build
pipelines, rigid protocols. In a data-consolidation and governance context,
Accretive Rigor treats institutional knowledge itself as a dynamic data layer
rather than static documentation. It guarantees that subsequent sessions inherit
an operational posture and a working style, not only raw facts.

## Practice (how AR shows up in a session)

- Spend real time on setup; the upfront rigor compounds into every later run.
- When a workflow is run, capture its verified learnings as a recipe or memory so
  the next run does not rediscover them.
- On new verified learnings about something that already has a recipe, author the
  next version rather than editing in place, so provenance accretes.
- Watch for twofers (one action, several benefits) and avoid negative twofers (one
  choice that cascades restrictions or silent failures).

## Changelog

- 1.0.0: initial. Generalized definition of Accretive Rigor: the two-halves
  alignment (Accretion + Rigor), rigor scoped to evidence rather than obedience,
  deliberation as a first-class half, scale invariance, and knowledge as a living
  data layer.
