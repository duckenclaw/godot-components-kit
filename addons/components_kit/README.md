# Components Kit (`components_kit`)

A saveable, event-driven Health component and a genre-agnostic StateMachine + State base for players, enemies and NPCs.

Part of the **[godot-game-kit](https://github.com/duckenclaw/godot-game-kit)** modular
template ecosystem — a set of reusable Godot 4 addons shared across FPS,
third-person, 2D sidescroller and top-down game templates.

## Install

**Git submodule (recommended)** — this repo is root-layout, so it drops straight
into a project's `addons/`:

```bash
git submodule add https://github.com/duckenclaw/godot-components-kit addons/components_kit
git submodule update --init
```

Then enable **Components Kit** in *Project → Project Settings → Plugins*.

**Godot Asset Library** — an Asset-Library-compatible release (files wrapped under
`addons/components_kit/`) is published per tagged version; search for "Components Kit" in the
editor's AssetLib tab.

## Dependencies

none (Health uses Game Core's EventBus/GameSettings if present)

## Versioning

Semantic versioning via git tags (`v1.0.0`). The Asset Library entry tracks tags.

## License

MIT — see [LICENSE](LICENSE).
