# builderforce-spawn

> Part of [Builderforce open source](https://builderforce.ai/open-source): the MIT projects Builderforce.ai is built on.

**Spawn** — build Roblox games by talking. A desktop app plus a Roblox Studio bridge.

## Layout

| Path | What |
|---|---|
| `spawn/` | Spawn desktop app (Tauri: `src-tauri/`, `ui/`) |
| `crates/bf-roblox` | Roblox Studio bridge |

`bf-cloud` (builderforce.ai sign-in and API client) comes from [builderforce-inference](https://github.com/SeanHogg/builderforce-inference) as a git dependency.

## Build

```sh
cargo build --workspace
```

History was extracted from `SeanHogg/Builderforce.ai` (`desktop/`).

## License

MIT
