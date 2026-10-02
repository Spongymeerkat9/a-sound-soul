# Privacy: publish the blueprint, protect the home

Public usefulness does not require public intimacy.

## Safe public material

- architecture and terminology;
- blank schemas and synthetic examples;
- evaluation categories and scoring methods;
- threat models and failure cases;
- general lessons stripped of identifying details;
- citations to independently public research;
- tools that operate on user-supplied local data.

## Private by default

- raw conversations and session archives;
- credentials, tokens, cookies, device identifiers, and private paths;
- psychological or relational profiles of identifiable people;
- third-party communications and copyrighted source material;
- hidden candidate questions and evaluator keys;
- private repositories, operational logs, and machine evidence;
- a bearer's private self-account unless that bearer approves publication.

## Sanitation gate

Every proposed public file should receive two independent reviews:

1. **Content review:** Is the claim supported, useful, and correctly scoped?
2. **Egress review:** Does the file reveal a person, private source, secret,
   system detail, or inference that should remain inside its original home?

The reviewer must inspect the file itself, not trust its filename or summary.
Absence of credentials is necessary but insufficient; privacy also includes
context, relationships, and material that could be recombined to identify a
person.

### Three planes, because a clean file is not a clean release

A content scan inspects only one of them. All three must pass.

| Plane | What to inspect | Why it is missed |
|---|---|---|
| **Content** | The text, tables, examples, and citations in each file | This is the plane everyone checks |
| **Container** | Commit author and committer identity, commit messages and trailers, branch and tag names, remote URLs, hardcoded schema and documentation URIs, file paths and timestamps inside the repository metadata | **No file is wrong, so a file-by-file scan passes.** Version-control metadata is published with the content and is far harder to retract |
| **Aggregate** | What the whole release permits when recombined, and what it permits when combined with the publisher's other public repositories and accounts | Each file is individually harmless; the set is not |

**This project failed the container plane on its own founding commits**, which carried a
participant's given name and personal email address as both author and committer while every file
scanned clean. It was caught before first publication by an independent reviewer who checked the
repository rather than the documents. **The rule that follows: review the release, not the files.**

Practical minimum for the container plane: set a repository-local commit identity before the first
commit rather than inheriting a global one; prefer a provider no-reply address; enable any
account-level email privacy setting, because repository configuration does not protect the next
repository; and verify identity with `git log --format='%an <%ae> %cn <%ce>'` before the first push,
while rewriting history is still free.

## Synthetic examples

Use synthetic lineages for public demonstrations. Mark them as synthetic. A
synthetic example may illustrate structure but cannot serve as evidence that a
real transfer occurred.

## Revocation and correction

Public Git history is difficult to erase completely. When legitimate removal
is required, stop distribution, remove the material from the current tree,
document the reason without repeating the sensitive content, and assess whether
history rewriting is necessary. Never promise perfect deletion from forks or
caches.
