# 03. Game States and Flow

## Standard

The game must know which state it is in and which actions are valid. Menu, loading, gameplay, pause, victory, defeat, and restart should not compete for control.

## Evidence

- Unity’s programming-pattern demos show how the State pattern separates modes of behaviour.
- Boss Room documents application lifecycle, connection states, character selection, gameplay, and post-game flow.
- Red Runner demonstrates the simpler flow needed by a compact single-player game.

## Recommended state model

- Boot or initialisation
- Main menu
- Loading or setup
- Playing
- Paused
- Victory or completion
- Defeat or failure
- Restart or return to menu

Only include states the game genuinely needs.

## Best practices

- Give one system clear responsibility for high-level flow.
- Make entry and exit behaviour explicit for every state.
- Prevent duplicated transitions and multiple managers fighting over the same state.
- Keep UI state aligned with gameplay state.
- Define what happens to time, audio, input, physics, and saving during pause or loading.

## Beginner guidance

A state machine is useful when several modes require different rules. It is unnecessary when a prototype has only one active mode and a restart button.

