# Stalker-14-EN Developer Wiki

Stalker-14-EN is an English-language SS14 mod built on top of a closed Russian Stalker-14 fork. The main repository is [coolmankid12345/stalker-14-EN](https://github.com/coolmankid12345/stalker-14-EN). This wiki covers the EN-specific systems, conventions, and architecture.

These pages focus on **why** systems exist, **how** they fit together, and **where** to look when you need to change something.

## Quick Links

| Resource | Link |
|----------|------|
| Discord | [Join the Discord](https://discord.gg/PMhEtkXFEa) |
| SS14 Developer Docs | [docs.spacestation14.com](https://docs.spacestation14.com/) |
| Repository | [coolmankid12345/stalker-14-EN](https://github.com/coolmankid12345/stalker-14-EN) |

## Getting Started

- [Dev Environment Setup](https://docs.spacestation14.com/en/general-development/setup/setting-up-a-development-environment.html)
- [Codebase Architecture](Codebase-Architecture)
- [Contributing Guide](Contributing-Guide)

## Features

| Page | Description |
|------|-------------|
| [Mob Variant and Trophy System](Mob-Variant-and-Trophy-System) | Randomized mutant variants with tiered loot drops and trophy extraction |

## Project Lineage

```
Space Station 14 (upstream engine + content)
  +-- Stalker-14 (closed Russian fork)
       +-- coolmankid12345/stalker-14-EN (English localization + new features)
```

All EN-specific code lives under `_Stalker_EN/` directories. Upstream Stalker code lives in `_Stalker/` directories. Base SS14 code sits outside both. This three-layer separation is the most important convention in the codebase. See [Codebase Architecture](Codebase-Architecture) for details.
