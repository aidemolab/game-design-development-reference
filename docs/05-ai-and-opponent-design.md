# 05. AI and Opponent Design

## Standard

Good game AI supports the intended player experience. It does not need to be perfectly intelligent; it should be readable, sufficiently challenging, fair, and consistent with the opponent’s role.

## Transferable lessons

- Stronghold Crusader demonstrates memorable AI personalities through different economic priorities, castle preferences, unit choices, aggression, and attack timing.
- OpenRA demonstrates strategy AI operating within deterministic game rules.
- Boss Room demonstrates spawning, character actions, and networked gameplay objects.
- Cataclysm: DDA shows how interacting systems can produce emergent situations.

## AI design layers

1. **Perception:** what the agent can detect or remember.
2. **Decision:** how it chooses a goal or action.
3. **Execution:** movement, attack, construction, retreat, or communication.
4. **Feedback:** how the player understands the decision.
5. **Difficulty adjustment:** timing, accuracy, resources, coordination, or planning depth.

## Best practices

- Give opponents strengths, weaknesses, and readable signals.
- Prefer different priorities over hidden statistical cheating.
- Separate sensing, decision-making, and action execution.
- Use state machines for simple agents, behaviour trees for branching behaviours, and utility scoring for competing goals when justified.
- Test whether players can learn and counter the behaviour.

## Originality boundary

Use the principle of distinct strategic personalities, but do not copy Stronghold’s named lords, dialogue, castle layouts, exact build orders, or unit combinations.

