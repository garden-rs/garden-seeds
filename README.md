# Garden Seeds

Seeds help gardens grow.

This is my personal collection of reusable templates for
[Garden](https://gitlab.com/garden-rs/garden).

Garden is a developer tool for working with collections of Git worktrees.


## Usage

Add this snippet to your `garden.yaml`:

```yaml
garden:
    includes: garden-seeds/templates.yaml
trees:
    garden-seeds: https://gitlab.com/garden-rs/garden-seeds.git
```

And then run:

```bash
garden grow garden-seeds
```

The templates, variables and commands are now available in your `garden.yaml`.
