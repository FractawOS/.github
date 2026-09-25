# Contributing to FractawOS

Thank you for contributing to FractawOS.

The project is designed around a modular architecture, so contributions should preserve clear boundaries between the core platform and optional modules.

## Ways to contribute

You can contribute through:

- bug reports;
- documentation improvements;
- feature proposals;
- architecture discussions;
- pull requests;
- module development;
- SDK improvements;
- registry submissions.

## Before writing code

For small fixes, a pull request may be opened directly.

For new subsystems, major architectural changes, new public APIs, or changes to the module contract, open an issue first.

This allows the design to be discussed before implementation begins.

## Architectural boundaries

The FractawOS Core should remain generic.

Domain-specific behavior should normally live inside modules.

Examples:

- development-specific behavior belongs in FractawDevModule;
- gaming-specific behavior belongs in FractawGameModule;
- music and instrument-processing behavior belongs in FractawAudioModule.

Modules must interact with the platform through public FractawOS APIs and FractawModuleSDK contracts.

A module should not rely on private Core implementation details.

## Module contributions

Community modules may be maintained outside the FractawOS organization.

A module does not need to become Official in order to be distributed.

Developers may submit compatible modules to FractawModuleRegistry.

Registry acceptance and Official status are separate processes.

## Pull requests

Pull requests should:

- have a clear purpose;
- remain focused;
- include relevant tests when applicable;
- update documentation when behavior changes;
- avoid unrelated refactoring;
- explain architectural changes.

Large changes may be split into multiple pull requests.

## Commit style

Use clear and concise commit messages.

Conventional Commits are recommended.

Examples:

```text
feat: add module lifecycle state
fix: prevent duplicate group activation
docs: describe module policy inheritance
refactor: isolate resource manager interface
```
