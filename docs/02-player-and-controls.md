# 02. Player and Controls

## Standard

Controls should be responsive, predictable, and appropriate to the camera and platform. The player should understand what an input will do before pressing it and should receive immediate visual, audio, or physical feedback afterwards.

## Lessons from references

- Red Runner provides an approachable example of a player controller integrated with obstacles and failure.
- Boss Room separates player intent, character actions, animation, and network authority.
- Unity FPS Sample illustrates the added complexity of aiming, movement, weapons, prediction, and multiplayer.
- osu! shows that timing-sensitive games need exceptionally consistent input and feedback.

## Best practices

- Use Unity’s current Input System for new Unity projects unless a project constraint justifies otherwise.
- Separate input reading from movement or action execution.
- Expose movement speed, acceleration, jump force, or sensitivity as configurable values.
- Test keyboard, controller, and accessibility needs deliberately; do not assume one scheme suits all players.
- Prevent physics-driven characters from tipping or tunnelling when the design requires stable movement.
- Make failure caused by controls feel explainable rather than arbitrary.

## Scope warning

Do not begin with parkour, vehicles, climbing, swimming, combat combos, and multiple devices simultaneously. Build and tune the minimum movement set first.

## Acceptance checks

- Input produces consistent results at different frame rates.
- Movement fits the camera perspective.
- The player cannot leave the valid play area accidentally.
- Controls can be explained in one short instruction panel.
- The player can distinguish input failure from game-rule failure.

