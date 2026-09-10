# Update Workflow / 更新流程

The private repository `ivan-misner-wisdom-agent` remains the source of truth. This public showcase is a reviewed, sanitized snapshot and is never automatically synchronized with the private research workspace.

## Release flow

```text
private research update
→ review evidence and rebuild persona
→ select public-safe changes
→ copy only approved showcase files
→ run release audit
→ inspect diff and file list
→ commit to public repo
→ tag a new version
→ publish release notes
```

## What may be updated

Public updates may include corrected persona wording, theory summaries, source links, terminology explanations, methodology clarifications, evidence samples, and rights or disclaimer wording.

## What must remain private

Do not copy raw sources, staging files, pending or rejected reviewer notes, Tavily queries or artifacts, API workflows, secrets, terminal logs, Manus task history, full evidence data, private vector indexes, working code, or website/chatbot implementation into this repository.

## Versioning

Use a new release tag for meaningful public snapshots, for example `v1.1.0` for content additions or corrections and `v1.0.1` for small wording or link fixes. Keep the private repository's commit history separate from this repository's public history.

## Maintainer checklist

1. Review the proposed public diff.
2. Run secret, raw-source, identity, terminology, Traditional Chinese, JSON, Markdown-link, and file-list checks.
3. Confirm the six theory status labels remain honest.
4. Confirm third-party names, marks, books, and quotations are not accidentally relicensed.
5. Commit only the sanitized snapshot.
6. Create a release note explaining what changed and what remains private.
