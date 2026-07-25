# Project Learning Tutor Skill

A Codex skill for systematically learning, dissecting, and mastering engineering projects.

Use this skill when you want an agent to teach a codebase as a long-term learning track, not just answer isolated code questions. It is especially useful for architecture understanding, evidence-cited code explanation, core workflow tracing, engineering tradeoff analysis, resume packaging, and interview preparation.

## Status

Current version: v0.2.0

This is a prompt-workflow skill. It does not include an automatic code indexer, static analyzer, grader, or project-specific parser. It improves reliability by requiring source evidence, archive templates, explicit uncertainty, and safe repository exploration.

## What It Helps With

- Build a clear mental model of a project.
- Trace real request, data, and control flows through code.
- Understand module responsibilities and boundaries.
- Separate code facts, documentation claims, and model inferences.
- Maintain cross-session learning records.
- Prepare resume bullets and interview explanations.

## What's New In v0.2.0

- Added evidence rules for code explanations.
- Added four learning modes: overview, deep dive, review, and interview simulation.
- Added configurable question density.
- Added large-repository and safety guidance.
- Added structured learning archive templates.
- Added Codex UI metadata in `agents/openai.yaml`.
- Added an MIT license.

## When To Use It

Use this skill at the start of a learning-focused session, for example:

```text
Use project-learning-tutor to help me learn this project from the architecture first.
```

```text
Use project-learning-tutor and continue from my existing learning archive.
```

```text
Use project-learning-tutor in interview simulation mode for the Agent workflow.
```

## When Not To Use It

This skill is not meant for quick one-off fixes or pure implementation tasks. For bug fixing, feature work, CI/debugging, or deployment, use the appropriate development workflow and keep this skill as learning context only.

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
|-- LICENSE
|-- README.md
`-- project-learning-tutor/
    |-- SKILL.md
    |-- agents/
    |   `-- openai.yaml
    `-- references/
        `-- archive-templates.md
```

## Skill File

The actual skill instructions live in:

[project-learning-tutor/SKILL.md](project-learning-tutor/SKILL.md)

## Compatibility

This skill follows the Agent Skills pattern: a skill folder containing a required `SKILL.md` file with YAML frontmatter. It is intended for Codex and compatible agent-skill environments.

## License

MIT
