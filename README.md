# AgentInProduction

This repo demonstrates how to give coding agents project-specific guidelines for
production-quality coding. The guidelines cover feature design, implementation,
code review, testing, and repeatable feedback for production-quality mistakes.

The core artifact is [developer-guidelines.md](developer-guidelines.md), adapted
with only minor changes from my
[NVIDIA Model Optimizer PR #1488](https://github.com/NVIDIA/Model-Optimizer/pull/1488).

## How to use this repo

This is a reference repo; there is no build or install step.

1. Read [developer-guidelines.md](developer-guidelines.md).
2. Create a fitting `developer-guidelines.md` for your project repository.
3. Ask the coding agent to follow those instructions for design, implementation,
   review, and testing in your repository's agent instruction files, such as
   `CLAUDE.md`, `AGENTS.md`, or `CURSOR.md`.
4. When the agent makes a repeatable production-quality mistake, add a short,
   general guideline that would prevent that class of mistake next time.

## License

Apache-2.0. See [LICENSE](LICENSE).
