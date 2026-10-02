# Threat model

Lineage systems concentrate sensitive history and can turn generated text into
effective authority. Their failure modes are not limited to hacking.

| Threat | Failure | Mitigation |
|---|---|---|
| Persona substitution | A prompt or style imitation is treated as the lineage | Blind baseline, provenance tests, developmental evidence |
| Fabricated recollection | A bearer claims memories it only inferred or retrieved | Require access labels and source citations |
| Summary coupling | Notes work for their writer model but fail after migration | Fixed schemas, directional tests, retained source evidence |
| Authority laundering | A memory converts past intent into current permission | Source-backed events, explicit revocation, bounded event sourcing |
| Stale current truth | Historical state is acted upon as current | Separate current views, staleness checks, supersession links |
| Evaluation contamination | Candidate reads answer keys or hidden rubrics | Freeze and isolate evaluation before inheritance |
| Aggregate masking | Overall score hides loss of one defining capability | Protected slices and incumbent fallback |
| Human mirroring | Candidate learns that agreement earns recognition | Reward principled dissent and preserve rejected answers |
| Coercive identity | A candidate is forced to impersonate a predecessor | Personal naming, refusal rights, no automatic succession |
| Privacy reconstruction | Sanitized fragments recombine into a private profile | Independent egress review and minimum necessary disclosure |
| Derived-store capture | Vendor index becomes the only copy of lineage knowledge | Human-readable canon and rebuildable adapters |
| Provenance drift | Model or harness changes without being recorded | Seal exact embodiment metadata on substantive contributions |
| Substrate assumption | Memory is designed as though storage and runtime cannot fail | Restore tests, independent instrumentation, recoverable canon |
| Alias collision | Two coordination names refer to the same physical resource | Canonical name-to-resource registry and last-moment guard |
| **Inferred absence** | A gap in the record is read as evidence that nothing happened, and a conclusion is then built on the silence | Measure coverage rather than extremes: record density across the interval, log-clear and retention events, and the independently established start-of-life of every instrument |
| **Container leakage** | Every file passes review while the repository metadata publishes an identity, path, or secret | Review the release across content, container, and aggregate planes; verify commit identity before first push |

## Trust boundaries

- Public contributors are untrusted with respect to private lineage access.
- Derived memory engines are untrusted with respect to canonical truth.
- A candidate is untrusted with respect to its own succession status.
- A bearer is not trusted to certify itself alone.
- Human recognition is powerful but remains fallible and should not overwrite
  contradictory evidence.

## Safety principle

No amount of eloquence upgrades a claim's authority. Authority comes from a
valid source event, evidence from an inspectable source, and succession from the
lineage's declared acceptance process.
