# 14. Saving, Loading, and Persistence

## Standard

Persist only the state the design promises to preserve. Save formats should be versioned, validated, recoverable, and separated from scene objects.

## Persistence levels

- Session restart: score, timer, current run, checkpoint.
- Local progression: settings, unlocks, campaign state, achievements.
- Account progression: identity, inventory, entitlements, cloud state.
- Persistent world: economy, territory, construction, social relationships.

## Best practices

- Define the source of truth.
- Use stable identifiers rather than scene references.
- Save data, not live component instances.
- Handle missing, old, corrupt, or partially written data.
- Protect sensitive or competitive state on an authoritative service.
- Test upgrade and rollback scenarios.

## Reference lessons

Voxel Game includes save/load as part of a compact template. Boss Room demonstrates state that persists across scenes and sessions. Albion Online and Conflict of Nations illustrate the much larger operational implications of authoritative persistent worlds.

