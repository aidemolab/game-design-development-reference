# 01. Game Concept and Core Loop

## Standard

A game concept should explain the player fantasy, objective, repeated actions, pressure, and reward in plain language. If the core loop cannot be described briefly, the design is probably not ready for implementation.

## Core-loop model

1. **Observe:** understand the current situation.
2. **Decide:** choose an action with a meaningful trade-off.
3. **Act:** move, build, collect, fight, negotiate, or solve.
4. **Receive feedback:** see the immediate consequence.
5. **Progress or recover:** gain capability, information, position, or another attempt.

## Evidence and comparison

- Red Runner demonstrates a compact loop: run, avoid obstacles, score, fail, restart.
- PUBG adds changing spatial pressure: land, loot, position, survive, confront.
- Stronghold Crusader connects economy, construction, defence, army production, and siege.
- Age of Empires connects gathering, expansion, technological advancement, counters, and conquest.
- Mindustry connects extraction, production, defence, expansion, and optimisation.

## Best practices

- Give the player an understandable short-term goal and a longer-term purpose.
- Ensure repeated actions produce visible consequences.
- Create decisions, not chores: two options should have different costs or risks.
- Use escalating pressure to prevent the optimal strategy from becoming passive.
- Prototype the loop before adding narrative, content volume, or advanced visuals.

## Scope warning

Persistent economies, large technology trees, live-service progression, and complex multiplayer loops should not enter the first prototype. Test one satisfying cycle first.

## Design questions

- What does the player do every 10–30 seconds?
- What changes because of that action?
- What creates risk, urgency, or uncertainty?
- Why would the player repeat the loop?
- What ends a session, round, mission, or match?

