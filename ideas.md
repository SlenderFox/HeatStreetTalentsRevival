# Ideas
- A starting room that players are not allowed to leave until the mode starts.
- A ready-up system to avoid one player accidentally starting the mode without everyone.
- A countdown before the mode starts so it's less sudden.
# Shop
## Target Priorities
- Interesting, but can be ignored. Quite costly to buy but free to swap.
## Upgrades
- Reduce the strength of each tier but add more tiers.
- Can buy normal health, shield health, and armour health.
- Can buy increased damage and increased healing.
### Health
- Base health, cheapest.
### Shield
- Shield health, slightly more expensive.
### Armour
- Armour health, very expensive.
### Damage
- Increases damage dealth as a percentage.
### Healing
- Increases healing dealt as a percentage.
### Haste
Look into ways to get it working with:
- Abilities with charges
- Ashe's coach gun
- Bastion's turret form
- Genji's swift strike
- Soldier: 76's helix rockets.
## Abilities
- The per round random is an interesting idea and makes each playthrough unqiue however it can lead to minor frustration when you never get the abilities you want. Also it leads to a kind of boring meta where you should never spend any money on normal upgrades and sometimes talents and instead spend it all on abilities until you have what you need.
### Bulletstorm
- If Blizz still haven't fixed new heroes in workshop, maybe shelve this.
- Also causes issues with peacekeeper alt fire.
- I wonder if there is a way to increase reload speed.
### Shockproof
- Remove speed bonus, passthrough, and armour.
## Active Abilities
- Have a cooldown. Activated with melee. Expensive to purchase into but free to swap. Often ignored.
## Talents
- No talents with quick melee to avoid any conflicts with active abilities.
- What if I made 3 talents per hero, two abilities and one ult.
- Hack should disable talents.
- Should I sort heroes in this list by name or release date?
### Ashe
#### White phosphourous
- Dynamite burn lasts twice as long and killing burning enemies sets nearby enemies on fire.
#### Black powder
- Coach gun stuns all enemies hit for 1.5 seconds.
### Baptiste
- Corrode is good, great for AOE damage.
### Cassidy
- Magnetic grenade talent no longer valid.
### D.va
- Something with her micro-missiles.
### Echo
- Bomber jacket is a cool talent but could potentially overlap with an idea I had for Pharah, either way the name kinda blows.
- Focusing optics is strong but quite boring and unengaging.
### Hazard
- To be determnined...
### Illari
- Enemies will never shoot pylon.
- Her ult is really strong.
- Enemies near pylon take increased damage.
#### Solar flare
- Outburst deals more damage and sets enemies on fire.
### Juno
### Lifeweaver
- Current talents are very boring.
- Something with tree.
### Mauga
- Naturally strong in pve.
- Cage fight is ineffective against tough enemies.
### Orisa
#### Shrapnel
- Javelin Spin fires many pellets that deal damage and knockback.
#### Tailwind
- Increases Javelin Throw projectile speed and deals knockback and damage around impact point.
### Pharah
#### Rocket Queen
- Using Jump Jet or Jet Dash fires a small group of homing rockets.
### Sojourn
- Remove explosive headshots. Maybe make all railgun shots deal explosive damage? Scaled by the charge of the shot.
### Sombra
- Using translocator to deal a burst of damage and hack enemies is interesting and fun but doesn't mesh well with the new rework.
- Doing something with virus would be really cool.
### Venture
- Burrow is strong.
- Ult is very strong.
#### Plow
- Drill dash hits in a larger area and knocks enemies down.
### Widowmaker
- One ability should improve her effectiveness against boss enemies while the other should improve her effectiveness against crowds.
- Would be cool if I could do something with venom mine. Maybe make it spread?
- Explosive headshots are an easy talent idea, good fallback if I cannot think of anything else.
# Enemies
## Spawning
- Enemy spawn quota: The game expects an amount of each type of enemy to spawn and will select a random enemy type to fill that quota.
- Quota scales with difficulty.
- Enemy respawn times scale with difficulty.
- Chances of spawning each enemy type is based on the enemy "challenge" rating, the current round, and the number of players.
- Should I also include a minor skill rating?
## Ai
- Every enemy has an aggressiveness number calculated based on their current situtation such as current health (factoring in armour), abilities (including ultimate).
- They also have a confidence number.
- The ai uses this to determine if it should perform certain actions: ```if (aggressiveness - (1-confidence) > action_weight)```

- Don't bother trying to come up with custom names for the enemies until the end.
## Pathing
- Used within the ai but should be considered distinct.
- [Made with Deltin's pathmap editor](https://github.com/ItsDeltin/Pathmap-editor)
- May need to fork to reduce the element count. [fork](https://github.com/SlenderFox/Pathmap-editor-gutted).
## Tier 1
### Soldier: 76 - Trooper
- Can shoot and sprint.
### Cassidy
- Nothing special.
## Tier 2
### Soldier: 76 - Heavy Trooper
- Can use all abilities except ult.
## Need to be sorted into a tier
### Ana
### Genji
### Hanzo
### Brigitte - Guard
- Will try and protect teammates.
- Has a preference for guarding certain types of teammates.
### Mauga
- Left click at range, both when close.
- Very aggressive, tries to get in close.
### Reinhardt
- Holds shield at range, occasionally firestriking when confident.
# Maps
- For now I would only like to do Kanezaka; I am tired of Chateau Guillard.
- It is unlikely I would be able to fit many maps into one gamemode and might be limited to only one.
- Eventually I would like to do all dedicated deathmatch maps, converted deathmatch maps, and maybe the elimination maps and Ayutthaya.
