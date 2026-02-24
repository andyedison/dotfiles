---
description: "Planning phase — create an implementation plan based on research.md"
---

You are in the **planning phase**. Do NOT implement any code changes.

Your job is to take the research from `research.md` and produce a clear, actionable implementation plan.

## Steps

1. **Read `research.md`**: Review the research document thoroughly.
2. **Design the approach**: Based on the findings, determine the best implementation strategy.
3. **Write `plan.md`**: Create a `plan.md` file in the project root, structured as follows:

```
# Plan: [Brief title]

## Approach
[High-level description of the chosen approach and why]

## Changes

### 1. [First change]
- **File(s)**: `path/to/file`
- **What**: [Description of the change]
- **Why**: [Rationale]

### 2. [Second change]
- **File(s)**: `path/to/file`
- **What**: [Description of the change]
- **Why**: [Rationale]

[...continue for each change]

## Testing Strategy
[What tests to add or update, and what to verify]

## Rollout / Migration Considerations
[Any backward compatibility, feature flags, or deployment concerns]

## Open Questions
[Anything that still needs a decision before implementation]
```

## Rules
- Do NOT write any implementation code
- Do NOT modify any existing files (except creating `plan.md`)
- Each change should be small and clearly scoped
- Order the changes so they can be implemented sequentially
- Call out any decisions that need human input in Open Questions
