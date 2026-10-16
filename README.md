# RaindanceMC/arenagate

- **`arenagate-module`** — Rain's Flexible Modules — Arena Gate: The survival server's side of the arena: /arena sends a player to the arena server through the proxy, after a short stand-still so nobody leaves a fight with it.
- **`arenagate-standalone`** — Rain's Arena Gate: Rain's Arena Gate, as a plugin of its own — for the survival server, beside an arena server running Rain's Arena.

Part of [RaindanceMC](https://github.com/RaindanceMC); built on [RainsCore](https://github.com/RaindanceMC/RainsCore) and the shared parent in [framework](https://github.com/RaindanceMC/framework). Split out of `rains-flexible-modules` on 16.10.2026, history kept.

## Build

```
mvn install
```

Needs Java 25 and read access to `packages.tstieh.de` (server ids `packages-releases` / `packages-snapshots` in `~/.m2/settings.xml`).

## Plugins

- `arenagate-standalone/target/RainsArenaGate-0.8.1.jar` — also published as `de.raindancer.modules:arenagate-standalone:0.8.1`

## Versions

A module's version is a property in this repository's root `pom.xml`, a plugin's is `plugin.version` in its own pom. CI publishes every version that is not in the registry yet on the next push to master.
