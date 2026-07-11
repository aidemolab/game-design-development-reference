# AIDemoLab Game Design and Development Reference

An original, topic-led knowledge base for planning and reviewing game projects. It synthesises transferable lessons from official Unity samples, complete open-source games, focused architecture repositories, successful source-available games, and legitimate public material about closed-source games.

## Purpose

This repository is not a collection of copied game ideas or source code. It converts research into practical questions, standards, comparisons, scope warnings, and originality boundaries that can support future AIDemoLab games.

> Stage 1 gives us breadth. Stage 2 gives us confidence and weighting. Stage 3 converts the combined evidence into a practical knowledge base.

## How to use this reference

1. Begin with the game concept, player objective, and core loop.
2. Select only the systems needed for the first playable version.
3. Use the topic pages to compare possible approaches.
4. Record decisions in a Game Design Document before implementation.
5. Treat every cited project as evidence, not as a template that must be copied.
6. Recheck licences before reusing any code or asset.

## Reference guide

| Topic | Main question |
|---|---|
| [Game concept and core loop](docs/01-game-concept-and-core-loop.md) | What does the player repeatedly do, and why is it engaging? |
| [Player and controls](docs/02-player-and-controls.md) | How does the player act, move, and receive feedback? |
| [Game states and flow](docs/03-game-states-and-flow.md) | How does the game move between menu, play, pause, success, and failure? |
| [Code architecture and patterns](docs/04-code-architecture-and-patterns.md) | How should responsibilities be separated without overengineering? |
| [AI and opponent design](docs/05-ai-and-opponent-design.md) | How can opponents be readable, distinctive, fair, and scalable? |
| [Strategy, economy, and resources](docs/06-strategy-economy-and-resources.md) | Which resources create meaningful strategic trade-offs? |
| [Combat, units, and balancing](docs/07-combat-units-and-balancing.md) | How do roles, counters, and feedback create fair combat? |
| [Levels, worlds, and environments](docs/08-level-world-and-environment-design.md) | How does space shape challenge, choice, and pacing? |
| [Camera, visuals, and audio](docs/09-camera-visuals-and-audio.md) | How does presentation communicate state and strengthen identity? |
| [UI, feedback, and accessibility](docs/10-ui-feedback-and-accessibility.md) | Can players understand what happened and what to do next? |
| [Progression, rewards, and replayability](docs/11-progression-rewards-and-replayability.md) | How does play create mastery, variety, and reasons to return? |
| [Multiplayer and networking](docs/12-multiplayer-and-networking.md) | Is multiplayer essential, and what authority model does it require? |
| [Performance, testing, and optimisation](docs/13-performance-testing-and-optimisation.md) | What should be measured before it is optimised? |
| [Saving, loading, and persistence](docs/14-saving-loading-and-persistence.md) | Which state must survive a session or device restart? |
| [Production workflow and GitHub](docs/15-production-workflow-and-github.md) | How should work be structured, reviewed, and documented? |
| [Game design checklist](docs/16-game-design-checklist.md) | Are the important design decisions explicit? |
| [Scope and complexity guide](docs/17-scope-and-complexity-guide.md) | What belongs in the first playable version? |
| [Sources, licences, and attribution](docs/18-sources-licences-and-attribution.md) | What evidence supports the guidance, and what may legally be reused? |

## Evidence model

- **Core references:** current, authoritative, well-documented projects used for detailed guidance.
- **Supporting references:** valuable but older, specialised, large, or complex projects used for selected lessons.
- **Historical and design references:** influential or closed-source games used for context and general design principles only.

## Non-copying standard

Each lesson should separate:

- **Source observation:** what a reference demonstrates.
- **Transferable principle:** the general lesson that can apply elsewhere.
- **Original application:** a new implementation designed for the current project.
- **Originality boundary:** names, worlds, characters, artwork, audio, maps, exact rules, proprietary code, and distinctive expression that must not be copied.

## Current research base

The evidence includes Unity Technologies samples, community Unity games, focused C# and Unity architecture projects, mature open-source games, and design studies of PUBG, Albion Online, Stronghold Crusader, Conflict of Nations, and Age of Empires. See the [source register](docs/18-sources-licences-and-attribution.md).

## Status

Version 0.1, initial knowledge-base structure and consolidated guidance.

