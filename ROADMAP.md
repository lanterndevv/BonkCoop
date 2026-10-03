# Roadmap

This is the plan, not a promise: no dates, and the order may change. Ideas and bug reports are welcome
in [Issues](https://github.com/lanterndevv/BonkCoop/issues).

## Next

- **Multiplayer options menu**, with an **Options** button on the Multiplayer screen:
  - **Your own settings**, which only change your game: hide teammate projectiles and effects for
    less clutter on screen ([#2](https://github.com/lanterndevv/BonkCoop/issues/2)), and show or
    hide teammate markers, the team panel and the names above teammates. They are also saved in the
    mod's config file, so you can change them from your mod manager.
  - **Lobby rules**, set by the host next to Difficulty and the same for everyone: time limit to pick
    an upgrade, how long a revive takes, how enemy and boss health scale with more players, and
    whether XP is shared in full or split.
- **Finding your team**: teammate icons on the minimap and a health bar above each teammate.
- **When you are down**: a spectator camera, and you can see your own revive circle.
- **Connection**: on-screen notices for "connection lost" and "waiting for <player>".
- **Lobby**: "Ready" resets after a run, the host can kick players, Back asks before closing the
  lobby, and characters and maps show their in-game names.
- **Teammates look like themselves**: their selected skin, not the default one.

## Balance

- Scale XP, enemy waves and boss health better with the number of players.
- Make reviving take a moment instead of being instant.
- Kill counts, stats and "on kill" effects only count your own kills.

## Later

- Rejoin a run after a disconnect, and join a run that has already started.
- Co-op sounds, pings and a results screen for each player.
- Host migration: if the host leaves, the run carries on with someone else as host.
