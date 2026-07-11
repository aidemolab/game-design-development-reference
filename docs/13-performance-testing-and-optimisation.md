# 13. Performance, Testing, and Optimisation

## Standard

Measure before optimising. Establish target hardware, frame rate, memory budget, load time, and network expectations before selecting techniques.

## Reference lessons

- Boat Attack demonstrates mobile-oriented URP choices, LOD, Addressables, jobs, shaders, and custom render features.
- ECS Samples and Megacity Metro show data-oriented approaches for high entity counts.
- Unity’s object-pooling example demonstrates reuse for frequently spawned objects.

## Best practices

- Profile CPU, GPU, memory, rendering, physics, garbage collection, and loading independently.
- Test representative builds, not only the Unity Editor.
- Optimise the measured bottleneck.
- Use pooling only where spawning patterns justify it.
- Reduce unnecessary updates, physics checks, allocations, overdraw, and asset size.
- Maintain automated tests for rules and manual playtests for experience.

## Warning

DOTS, jobs, custom render passes, and aggressive pooling can add complexity. Adopt them only when evidence shows they solve a relevant constraint.

