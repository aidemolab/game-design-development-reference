# 09. Camera, Visuals, and Audio

## Standard

Presentation should make gameplay easier to understand and give the game a coherent identity. Visual effects and sound should reinforce state, action, danger, success, and failure.

## Reference lessons

- Boat Attack demonstrates Cinemachine, Shader Graph, volume blending, reflections, water effects, LOD, and mobile-aware URP production.
- Boss Room uses camera and animation as part of multiplayer character presentation.
- Red Runner demonstrates a compact, consistent visual identity supporting a simple loop.

## Best practices

- Choose camera perspective from gameplay needs, not visual fashion.
- Keep important targets readable against the background.
- Establish a small visual language for interactable, dangerous, collectible, and completed states.
- Use audio categories and centralised mixing.
- Reserve strong effects for important events.
- Test without sound and without colour to reveal missing feedback channels.

## Performance reminder

Lighting, shadows, particles, post-processing, water, transparency, and audio voices carry costs. Measure them on the target platform.

