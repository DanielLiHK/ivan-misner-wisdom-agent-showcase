# Update Workflow

The private research repository remains the source of truth. This public showcase is a reviewed snapshot and is not automatically synchronized with the research workspace.

## Release flow

```text
research update
→ review the supporting sources
→ select changes suitable for public explanation
→ update the relevant summaries
→ check wording, attribution, and boundaries
→ review the public changes
→ publish a versioned update
```

## What may be updated

Public updates may include corrected persona wording, theory summaries, source links, terminology explanations, methodology clarifications, evidence samples, and rights or disclaimer wording.

## What must remain private

Do not copy unpublished working materials, private notes, credentials, internal records, complete source collections, implementation code, or website/chatbot material into this repository.

## Versioning

Use a new release tag for meaningful public snapshots, for example `v1.1.0` for content additions or corrections and `v1.0.1` for small wording or link fixes. Keep the private repository's commit history separate from this repository's public history.

## Maintainer checklist

1. Review the proposed public diff.
2. Run secret, raw-source, identity, terminology, Traditional Chinese, JSON, Markdown-link, and file-list checks.
3. Confirm the six theory status labels remain honest.
4. Confirm third-party names, marks, books, and quotations are not accidentally relicensed.
5. Commit only the sanitized snapshot.
6. Create a release note explaining what changed and what remains private.
