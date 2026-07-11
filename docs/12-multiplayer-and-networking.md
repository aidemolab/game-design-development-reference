# 12. Multiplayer and Networking

## Standard

Multiplayer must serve the game concept. It adds authority, synchronisation, latency, matchmaking, security, testing, hosting, moderation, and operational requirements.

## Reference lessons

- Boss Room is a core reference for server authority, RPCs, replicated objects, latency masking, connection states, sessions, character selection, and multiplayer game flow.
- Megacity Metro demonstrates DOTS and large-scale Netcode for Entities.
- Mirror provides a mature open networking framework for Unity.
- Unitystation demonstrates the organisational cost of a large, persistent, collaborative multiplayer game.

## Best practices

- Decide who is authoritative for movement, combat, inventory, and victory.
- Design for latency and disconnection explicitly.
- Keep network messages minimal and meaningful.
- Test with simulated latency, packet loss, multiple clients, and reconnection.
- Protect server-side truth from client manipulation.

## Scope gate

If the core experience works as single-player, build and validate that version first unless multiplayer is inseparable from the concept.

