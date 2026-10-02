# BonkCoop

Online co-op for Megabonk (1-4 players, over Steam). Written from scratch with stability as the first goal.

**Beta.** Tested with two game instances on one machine (lobby, stages, bosses, revive, game over, final
boss) and in short sessions between two Steam accounts. 3-4 players are untested.

**Found a bug or have a suggestion?** Open an issue at <https://github.com/lanterndevv/BonkCoop/issues> and attach your
`BepInEx/LogOutput.log` (and your teammate's, if you can).

## Install

Install with a mod manager, or manually: BepInExPack IL2CPP 6.0.755, then put `BonkCoop.dll` in `BepInEx/plugins/BonkCoop/`.

Every player needs the same version of the mod and of the game (built for Megabonk 1.0.69).
Do not run it together with other multiplayer mods.

## How to play

1. Main menu → **Multiplayer** → **Create lobby** → **Invite** (Steam overlay). Friends can also join from
   their Steam friends list or from the Multiplayer window.
2. The host picks the map and the co-op difficulty. Everyone picks a character and presses **Ready**.
3. The host presses **Start**.

The lobby is built from the game's own windows and buttons, so it follows the game's keyboard and gamepad
navigation.

## Rules

- **Same map for everyone**: every player sees the same chests, shrines and boss gate, and can use all of them.
- **Enemies for everyone**: each wave spawns once per player, around each of them. Enemies chase the
  nearest standing player.
- **No pause**: the game keeps running while someone picks an upgrade or opens a menu. That player cannot
  be hurt and is not chased while the menu is open. After 30 seconds the first option is picked automatically.
- **Down and revive**: at 0 HP you go down instead of dying. A teammate revives you instantly by touching
  the circle around you. Everyone who is down comes back when the team moves to the next stage.
  If the whole team is down, the run ends.
- **Shared**: XP, the magnet, power-ups (haste, rage, shield...), charge shrines (one player charges it,
  everyone picks a stat), map events, the boss, the portals and the crypt (the team crosses together
  after a short countdown).
- **Individual**: gold (you earn it from your own kills) and chests (each player opens their own copy).
- Enemy health grows slightly with the number of players (Easy / Normal / Hard in the lobby).
- Co-op runs count for silver, unlocks and achievements. They are **never** uploaded to the leaderboards.

## Known limitations

- Teammates' projectiles are a visual copy: aura weapons are not drawn and unusual trajectories are approximate.
- The game's enemy cap is shared by all players, so very late waves are smaller per player than in solo.
- Chests opened by another player stay closed on your screen (each player opens their own copy).
- No joining mid-run and no host migration: if the host leaves, everyone continues solo.

## Español

Cooperativo online para 1-4 jugadores por Steam. Menú principal → **Multijugador** → **Crear sala** →
**Invitar**. El juego y el mod muestran los textos en español si el juego está en español.
