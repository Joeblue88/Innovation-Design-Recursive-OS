# Contributing to Innovation Design Recursive OS

Thanks for your interest in improving ID-ROS. This document explains how to propose changes, add new skill modules, and keep the system internally consistent.

## Ground Rules

ID-ROS is a **recursive framework**, not a linear playbook. Contributions should preserve the feedback-loop logic and the separation of concerns between the meta-orchestrator and individual skill modules. Before opening a pull request, please skim the `README.md` to make sure your proposal fits one of the five core modules — or makes a deliberate case for a sixth.

## Ways to Contribute

- **Refine an existing skill** — sharpen a framework, add a tool, clarify a trigger.
- **Add a new template** — workshop canvases, audit checklists, or facilitation worksheets.
- **Extend the meta-orchestrator** — propose new dependency protocols or trigger logic.
- **Improve documentation** — examples, walkthroughs, translations, diagrams.
- **Report friction** — open an issue describing where the system breaks down in practice.

## Style & Conventions

All content must be in English. Use clear, concrete language; avoid jargon when a plainer word will do. YAML files follow this pattern:

- `name`: snake_case identifier
- `frameworks`: list of named frameworks the module draws from
- `core_logic`: one short paragraph explaining the module's job
- Module-specific keys (e.g. `tools`, `intervention_gates`, `modules`) follow

Markdown templates should be self-contained worksheets a facilitator could print and use without further context.

## Workflow

1. Fork the repository and create a branch named after your change (`feature/cla-template`, `fix/foresight-typo`).
2. Make your changes in small, focused commits with descriptive messages.
3. Run a quick self-review against the questions below.
4. Open a pull request describing **what** you changed, **why**, and **which module(s)** it touches.

## Self-Review Checklist

- Does the change preserve the recursive feedback-loop logic?
- Is the trigger or activation condition explicit?
- Does it respect the Ethics Gate when the change touches data, technology, or vulnerable users?
- Is the language English and free of institution-specific references?
- If you added a new module, did you also register it in the meta-orchestrator's dependency protocols?

## Issue Triage

When opening an issue, please include: the module affected, the situation where the framework felt incomplete or wrong, and (if possible) a suggested direction. Issues without a reproducible example will be closed after 30 days of inactivity.

## License

By contributing, you agree that your contributions will be licensed under the MIT License that covers this project.
