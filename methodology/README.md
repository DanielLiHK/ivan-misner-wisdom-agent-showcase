# Methodology / 研究方法

## Purpose

This showcase explains the reasoning architecture used to organize public material. It does not publish the private research workbench or claim that the process captures every teaching by Ivan Misner.

## High-level workflow

```text
source selection
→ source classification
→ structured claim extraction
→ human review gate
→ duplicate and contradiction handling
→ terminology alignment
→ persona-layer placement
→ confidence and limitation labels
→ sanitized Markdown distillation
```

## Evidence categories

- **Documented:** a claim is tied to an identified public source.
- **Documented summary:** the project paraphrases a public source rather than presenting a full quotation.
- **Synthesis:** the project combines compatible claims across sources and labels the result as interpretation.
- **Application:** a possible way to use an idea in a conversation; it is not presented as Ivan Misner's words.
- **Needs research:** the public material is too limited for broader claims.

## Review principle

A model-generated proposal is not automatically evidence. Pending, rejected, or placeholder source records remain outside the public release. Public summaries preserve uncertainty and do not fill gaps merely to make the theory map look complete.

## What is not published

The private repository retains raw captures, research adapters, API workflow, complete evidence data, reviewer records, run metadata, and rebuild scripts. This public repository only explains the method at a conceptual level.
