# Changelog

## 0.3.0

Bug-fix release. Everyone needs to update: 0.3.0 cannot play with 0.2.x.

- XP orbs: fixed double XP with the magnet, orbs that paid nothing to whoever picked them up, lost XP
  with Echo Shard, and a corrupted orb list after many pickups. A downed player now receives the XP
  the team earned meanwhile when they get back up.
- Portal: a late key press can no longer skip a stage, the countdown is cancelled on game over, and
  the team waits for anyone still choosing an upgrade instead of discarding it.
- Crypt: entering or leaving revives downed players for everyone, and it can no longer be re-entered.
- Boss door: two presses at once no longer summon two bosses. Final boss: same pylons for everyone.
- The pause menu no longer makes you invulnerable (upgrade and chest windows still do, and keep you
  protected for a moment after you close them). Levelling up mid-air keeps your momentum.
- After one auto-pick timeout, later upgrades are no longer picked for you forever.
- When the last teammate leaves mid-run the game cleanly continues solo (no frozen host, stale HUD
  or hanging projectiles), and the next solo run is uploaded to the leaderboards again.
- Enemies: no more immortal ghost enemies on clients, spawns are shared fairly when the enemy cap is
  full, elite damage uses the attacker's own stat, and clients get swarm, miniboss and final swarm
  alerts.
- Network: a frozen or disconnected player is detected and dropped, a late map list is still
  applied, and the host ignores out-of-range or stale requests from guests.
- Guests join with their selected character instead of always Fox.
- New: an on-screen marker with name and distance points to teammates that are off screen or down.

## 0.2.1

- Documentation only: issues and feedback now live on GitHub. Same mod file as 0.2.0, so 0.2.0 and
  0.2.1 players can play together.

## 0.2.0

- You now see your teammates' projectiles (visual only; the damage still comes from their game).
- XP orbs drop on every player's screen. When one player picks an orb up, everyone gets that XP once
  and the orb disappears for all.
- Graves, coffins, eggs, statues and character fights can be used by any player and now play out on
  every screen (before, they just disappeared for the other players).
- The crypt works in co-op: the team enters and leaves together after a short countdown, the dungeon
  is the same for everyone and its boss is shared.
- All players must update: 0.2.0 is not compatible with earlier versions.

## 0.1.2

- Enemies now spawn around every player: each wave spawns once per player, around each of them.
  Before, everything spawned around the host and enemies far from the host were pulled back to them
  (this is also why a challenge shrine activated by a guest seemed to spawn nothing).
- Enemy health no longer scales much with player count (Normal: +25% per extra player); the extra
  difficulty comes from the extra enemies.
- Revive is instant: touch the circle around a downed teammate.
- Gold is individual: you earn the gold of the enemies you kill. XP is still shared.
- The magnet pulls every player's XP, whoever picks it up. Power-ups (haste, rage, shield, time...)
  picked up by one player are given to everyone.
- Desert storms and tornadoes are the same for all players.
- All players must update: 0.1.2 is not compatible with earlier versions.

## 0.1.1

- The map is now identical for every player. Chests, shrines, the boss gate and the rest were placed
  differently for players with different save files; the host's layout is now applied to everyone.
- Everything on the map can be used by every player, not only by the host (challenge shrines, graves, eggs...).
- Charge shrines are shared: when one player charges it, everyone gets the stat reward.
- No more global pause. The game keeps running while someone picks an upgrade; that player is
  protected and is not chased until they choose (30 second limit).
- All players must update: 0.1.1 is not compatible with 0.1.0.

## 0.1.0

- First beta: Steam lobby, shared world (map, enemies, timers), shared XP and gold, global pause,
  down/revive, team game over and restart, stage boss, portals, final boss and victory.
