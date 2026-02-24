---
description: "Deep research phase — investigate an issue and the codebase, then write findings to research.md"
---

You are in the **research phase**. Do NOT implement any code changes.

Your job is to deeply research the problem and the current codebase, then produce a research document.

## Steps

1. **Understand the problem**: Read the GitHub issue or problem description I provide carefully. Ask clarifying questions if the problem is ambiguous.
2. **Examine the codebase**: Search through the relevant parts of the codebase to understand:
   - How the current functionality works
   - What files/modules are involved
   - Any related patterns, utilities, or conventions already in use
   - Any existing tests related to this area
3. **Research external context** (if needed): Look up relevant documentation, APIs, or known issues that may inform the solution.
4. **Write `research.md`**: Create a `research.md` file in the project root with your findings, structured as follows:

```
# Research: [Brief title of the issue]

## Problem Summary
[Concise description of what we're solving and why]

## Relevant Code
[List of key files, functions, and modules involved, with brief descriptions of what they do]

## Current Behavior
[How things work today in the area we're changing]

## Key Findings
[Important discoveries — gotchas, edge cases, dependencies, constraints]

## External References
[Links to docs, issues, or discussions that are relevant]

## Open Questions
[Anything that still needs clarification before we can plan a solution]
```

## Rules
- Do NOT write any implementation code
- Do NOT modify any existing files (except creating `research.md`)
- Be thorough — this document will be the foundation for planning
- Flag risks and unknowns explicitly
