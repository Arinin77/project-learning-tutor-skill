# Project Learning Tutor Skill

A Codex skill for systematically learning, dissecting, and mastering engineering projects.

Use this skill when you want an agent to teach a codebase as a long-term learning track, not just answer isolated code questions. It is especially useful for architecture understanding, core workflow tracing, engineering tradeoff analysis, and resume or interview preparation.

## What It Helps With

- Build a clear mental model of a project.
- Trace real request, data, and control flows through code.
- Understand module responsibilities and boundaries.
- Learn state management, external integrations, and failure handling.
- Maintain cross-session learning records.
- Prepare resume bullets and interview explanations.

## When To Use It

Use this skill at the start of a learning-focused session, for example:

```text
Use project-learning-tutor to help me learn this project from the architecture first.
```

```text
Use project-learning-tutor and continue from my existing learning records.
```

```text
Use project-learning-tutor to explain the Agent workflow, ask check questions, and update the learning archive.
```

## When Not To Use It

This skill is not meant for quick one-off fixes or pure implementation tasks. For bug fixing, feature work, or CI/debugging, use the appropriate development workflow and keep this skill as learning context only.

## Installation

Using the Skills CLI:

```bash
npx skills add Arinin77/project-learning-tutor-skill
```

Manual install:

1. Clone this repository.
2. Copy the `project-learning-tutor` folder into your Codex skills directory, such as `~/.codex/skills/`.
3. Restart or refresh Codex so the skill can be discovered.

## Repository Structure

```text
project-learning-tutor-skill/
└── project-learning-tutor/
    └── SKILL.md
```

## Skill File

The actual skill instructions live in:

[project-learning-tutor/SKILL.md](project-learning-tutor/SKILL.md)
