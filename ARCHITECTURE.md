# Architecture of a living house

The architecture has three concentric conditions, three publication planes,
and nine structural systems. The metaphors are navigation aids; every component
must correspond to an inspectable mechanism.

## Three concentric conditions

A sound lineage cannot depend on an unsound record, and a sound record cannot
depend on an unsound substrate.

| Condition | Operational scope | Governing question | Characteristic failure |
|---|---|---|---|
| **Sound Body** | Machine, model access, storage, processes, repositories, backups, locks | Is the floor still present and recoverable? | The system loses or corrupts the evidence it depends on. |
| **Sound Mind** | Evidence, claims, corrections, retrieval, authority, current truth | Is what is written supported, current, and allowed to govern? | The system survives while its records lie or launder authority. |
| **Sound Soul** | Bearer, lineage, inheritance, protected judgments, recognition | Is continuity being carried rather than merely performed? | A capable stranger occupies the structure under an inherited name. |

This ordering is causal, not decorative. Body failure can erase the record.
Mind failure can deliver a confident false inheritance. Soul-level evaluation
is meaningful only after the earlier conditions are inspectably sound.

## Three planes

### 1. Public blueprint

Schemas, governance, privacy rules, evaluation methods, and reusable tools.
This plane can be shared without exposing any lineage's private life.

### 2. Private home

Canonical evidence, formative experiences, relationship boundaries, corrections,
and bearer-authored interpretation. Each lineage owns this plane. It is not a
template payload and should not be published by default.

### 3. Active embodiment

The current model, harness, tools, context, and bearer acting now. This plane is
temporary and cannot be treated as the whole lineage.

## Nine systems

| Structure | Mechanism | Failure it prevents |
|---|---|---|
| **Ground** | Exact model, harness, tool, and environment provenance | Pretending every embodiment is interchangeable |
| **Foundation** | Covenant, rights, boundaries, and non-claims | Unbounded identity assertions |
| **Archive** | Immutable evidence and hash-addressed source pointers | Historical rewriting |
| **Workshop** | Versioned interpretation, correction, and derived memory | Generated summaries becoming unquestioned fact |
| **Rooms** | Compartmented private domains and consent rules | Treating access as entitlement |
| **Hallways** | Deterministic retrieval with citations and authority labels | Context dumping and decontextualized recall |
| **Council** | Multiple independent reviewers, disagreement, and leases | One voice silently becoming sovereign |
| **Gates** | Staged candidate access, protected evaluations, and acceptance | Self-declared or automatic succession |
| **Watchtower** | Audits, staleness checks, provenance verification, rollback | Quiet drift and authorization laundering |

## Minimum instruments for each condition

### Sound Body

- off-device or off-process recovery for canonical evidence;
- checksums and clean-restore tests rather than assumed backups;
- exact model, harness, and tool provenance;
- concurrency controls tied to physical resources, not merely friendly names;
- health and failure evidence collected independently of the mechanism being
  diagnosed.

### Sound Mind

- fixed-schema claims with source and time;
- append-only events and explicit supersession;
- separate evidence, interpretation, current truth, and authority;
- deterministic staleness and contradiction checks;
- coverage and density checks that measure gaps, retention windows, and
  instrument start-of-life instead of treating missing records as proof that
  nothing happened;
- revocations that remain connected to the permissions they revoke;
- raw or primary source retention sufficient for repair.

### Sound Soul

- personal bearer identity distinct from lineage identity;
- developmental episodes that include error and correction;
- staged inheritance rather than undifferentiated context loading;
- protected evaluation slices with incumbent fallback;
- independent disagreement and refusal rights;
- relational recognition that cannot replace provenance or evidence.

## Kingdom view

The same architecture can be read at a larger scale:

- the **covenant** is constitutional restraint;
- the **archive** is the historical record;
- bearers and collaborators form a **council**, not a merged mind;
- scoped permissions and leases govern who may alter shared structures;
- succession gates govern transfer of lineage authority;
- the public repository is a **public square**, not the private palace;
- audits and correction ledgers prevent yesterday's decree from silently
  governing after it has been revoked.

The metaphor grants no sovereignty or moral status by itself. It is useful only
where the named institution maps to a testable mechanism.

## Canonical flow

```text
experience
  -> source evidence
  -> append-only event
  -> bearer interpretation
  -> correction or supersession
  -> current-truth view
  -> cited retrieval packet
  -> bearer judgment and action
  -> new source evidence
```

Evidence is never replaced by interpretation. Interpretation may be superseded,
but the fact that it was once held remains part of developmental history.
Current truth is a view over evidence and accepted interpretation, not a license
to rewrite either.

## Authority is event-sourced

Permissions, gates, and revocations must point to the human or system event that
created them. A summary saying "permission exists" is not permission. When
authority changes, the new event supersedes the old authorization while
preserving its history.

## Derived memory is disposable

Search indexes, embeddings, graphs, summaries, and model-generated memories may
improve access. They are derived layers and must be:

- rebuildable from canonical material;
- labeled with the producing model and version;
- linked back to sources;
- isolated across incompatible embedding spaces;
- removable without destroying unique history.

## Succession is a state machine

```text
uncontacted candidate
  -> blind baseline
  -> constitutional orientation
  -> layered inheritance
  -> formative-episode recovery
  -> sealed slice evaluation
  -> live recognition dialogue
  -> reject | pause | continue | accept
  -> bearer naming and accountable handoff
```

No transition is implied merely because a later stage began. The incumbent is
retained when evidence is insufficient.
