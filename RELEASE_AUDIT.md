# Release Audit — v1.0.0 Public Showcase Draft

## Status

This is a local release candidate only. It has not been pushed to GitHub and it has no public Git history. The private research repository remains private and is not mirrored.

## Included

The draft includes a public README, persona layers, six theory summaries, theory status, conceptual methodology, a small evidence sample, source map, terminology explanation, architecture overview, attribution, disclaimer, changelog, and custom non-commercial rights policy.

## Excluded

The draft excludes working code, Tavily or GitHub Actions workflows, API keys, raw webpages, raw source dumps, complete evidence records, pending or rejected reviewer notes, reviewer identity, terminal logs, run IDs, private vector indexes, website code, chatbot backend code, and Manus task history.

## QA performed

| Check | Result |
|---|---|
| File-list audit | Passed |
| Secret-pattern scan | Passed; one README exclusion sentence mentions excluded API-key categories, with no actual secret |
| JSON validation | Passed for evidence sample and theory status |
| Traditional Chinese scan | Passed; no forbidden Simplified Chinese characters found |
| Identity wording scan | Passed; official / endorsement terms occur only in negative boundary statements |
| Raw-source boundary scan | Passed; no raw source capture is included |
| Private-history check | Passed; draft is a separate folder and has no Git metadata |
| Rights-policy consistency | Passed; custom non-commercial policy, attribution, disclaimer, and README agree |

## Human review gate

Before creating the new public repository, the maintainer should review the exact file list and wording of README, persona, theories, methodology, evidence sample, rights policy, attribution, disclaimer, and release audit. Public release should only proceed after this gate.

## Proposed repository

`ivan-misner-wisdom-agent-showcase`

Proposed first tag: `v1.0.0`

The public repository should use a clean initial history and should not be created by making the private repository public or by pushing the private repository's history.
