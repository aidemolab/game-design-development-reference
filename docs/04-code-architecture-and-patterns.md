# 04. Code Architecture and Patterns

## Standard

Architecture should make the current project easier to understand and change. A pattern is a reusable way of thinking about a recurring problem, not code that must be copied into every game.

## Core principles

- **Single responsibility:** one component should have one clear reason to change.
- **Loose coupling:** systems should know only what they need to know.
- **Explicit dependencies:** required collaborators should be visible and testable.
- **Composition:** build behaviour from focused components rather than deep inheritance trees.
- **Data separation:** use data assets where designers need configurable values.

## Pattern guidance

| Pattern | Useful when | Avoid when |
|---|---|---|
| State | Behaviour changes between clear modes | Only one simple behaviour exists |
| Observer/events | Several systems react to one event | Direct communication is clearer and local |
| Object pool | Objects spawn and disappear frequently | Only a few objects exist |
| Factory | Runtime creation varies by type or data | One prefab is instantiated in one place |
| Command | Actions need undo, queues, replay, or remapping | A direct method call is sufficient |
| MVC/MVP | UI and logic require independent testing or replacement | A tiny screen has minimal logic |
| Service locator | Legacy/global service access must be centralised | It would hide dependencies in new code |

## Evidence weighting

Unity’s Game Programming Patterns Demo is a core conceptual source, but its repository does not contain a standalone licence file. Study the ideas and create original implementations rather than copying scripts into another project.

## Architecture review questions

- Can a beginner locate the code responsible for a feature?
- Can one system change without breaking unrelated systems?
- Are configuration values separated from hard-coded behaviour?
- Does the abstraction solve a present problem or an imagined future problem?

