# Learning Archive Templates

Use these templates when creating or normalizing a project learning archive.

Default path: `.codex-plans/<project-slug>-learning/`

If project instructions specify another path, use that path. If an existing archive uses `task_plan.md` instead of `learning_plan.md`, keep the existing convention.

## File: handoff.md

```markdown
# Handoff: <Project Name> Learning

## Current Position
- Date:
- Current phase:
- Current module or chain:
- Last completed unit:
- Next recommended step:

## Learner State
- Strengths:
- Weak points:
- Concepts to revisit:

## Source Boundaries
- Confirmed implementation facts:
- Documentation claims not yet verified:
- Known mismatch or uncertainty:

## Continue With
- Start here next session:
- Files or entry points to inspect first:
```

Update this file at the end of meaningful sessions. Keep it short enough to read first next time.

## File: learning_plan.md

```markdown
# Learning Plan: <Project Name>

## Goal
- Long-term learning goal:
- Resume/interview target:

## Learner Profile
- Current strengths:
- Weak or new areas:
- Preferred learning style:
- Pace:

## Scope
- In scope:
- Out of scope for now:

## Phases
- [ ] 1. Project goal and architecture map
- [ ] 2. Entry points and main request flow
- [ ] 3. Core domain chain
- [ ] 4. State, storage, and external systems
- [ ] 5. Reliability, safety, and failure handling
- [ ] 6. Evaluation and improvement opportunities
- [ ] 7. Resume and interview consolidation

## Decisions
| Date | Decision | Reason |
|---|---|---|

## Blockers
| Date | Issue | Attempt | Resolution |
|---|---|---|---|
```

Use `task_plan.md` instead when the project already uses that name.

## File: progress.md

```markdown
# Progress: <Project Name> Learning

## Session Log
| Date | Action | Result | Evidence |
|---|---|---|---|

## Completed Units
| Unit | Status | Should Not Re-teach From Scratch |
|---|---|---|

## Tests Or Experiments
| Date | Command/Setup | Result | Notes |
|---|---|---|---|

## Next
- Next learning unit:
- First files or routes to inspect:
```

Update when a unit is completed, a next step changes, or a useful experiment is run.

## File: assessments.md

```markdown
# Assessments: <Project Name> Learning

## Understanding Checks
| Date | Module | Question | Learner Answer | Assessment | Correction |
|---|---|---|---|---|---|

## Mastery Snapshot
| Topic | Level | Evidence | Next Correction |
|---|---|---|---|
```

Keep ordinary check questions here. Promote only durable questions to `review_questions.md`.

## File: review_questions.md

```markdown
# Review Questions: <Project Name>

## Questions
| Priority | Module | Question | Reference Points | Mastery | Last Reviewed |
|---|---|---|---|---|---|
```

Add a question only when it is worth long-term review: core mechanism, interview likely, weak answer, cross-module link, tradeoff, safety, reliability, evaluation, or project presentation.

## File: concept_glossary.md

```markdown
# Concept Glossary: <Project Name>

## Concepts
| Term | Plain Meaning | In This Project | Common Confusion | Interview Phrasing |
|---|---|---|---|---|
```

Use this file for concept boundaries, not general notes.

## File: findings.md

```markdown
# Findings: <Project Name> Learning

## Key Findings
- 

## Project Mental Model
- 

## Evidence
| Source/File | Lines | Finding | Type | Relevance |
|---|---|---|---|---|

## Implementation Boundaries
| Claim | Status | Evidence | Notes |
|---|---|---|---|

## Open Questions
- 
```

Use `Type` values such as `Code fact`, `Documentation claim`, or `Inference`.
