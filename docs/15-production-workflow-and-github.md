# 15. Production Workflow and GitHub

## Standard

Design decisions, source code, assets, tests, and releases should move through a visible, reversible workflow.

## Recommended workflow

1. Define the design decision or milestone.
2. Create a focused branch.
3. Implement one controlled change.
4. Test in Unity and inspect the Console.
5. Review changed files before committing.
6. Commit with a clear outcome-based message.
7. Push and preserve a clean checkpoint.
8. Update documentation when the design changes.

## Unity repository practices

- Use a Unity-aware `.gitignore`.
- Commit `.meta` files with their assets.
- Exclude generated folders such as `Library`, `Temp`, `Logs`, and build output.
- Use Git LFS deliberately for large binary assets.
- Keep project-owned content in a clear folder such as `Assets/_Project`.
- Avoid unrelated changes in one commit.

## Portfolio standard

Original projects should be pinned above reference forks. Fork only when modification, contribution, or long-term maintenance justifies it. Study and cite by default.

