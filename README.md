# 🧬 Venom Evolution: Smart Farm

A smart auto farm for **Venom Evolution** on Roblox. It trains, fights, collects wins and evolves for you, and it always does whatever gets you furthest fastest.

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/headshot7535-png/Venom-Evolution/main/VenomEvolution_SmartFarm.lua"))()
```

## What to farm
Pick one of six on the Home tab:

| | Mode | What it does |
|---|---|---|
| 🧠 | **Smart** | Trains or fights, whichever gets you to your next Evolve fastest. On the last strain it opens new stages, else trains. |
| 🚀 | **Progress** | Fights the next stage you haven't beaten, travels to each new world as it opens and evolves the moment it can. When a boss is too strong for you yet, it trains and evolves until it isn't. |
| 🎵 | **Train** | Stands you on your best sound pad and evolves when it can. |
| ⚔️ | **Stages** | Clears the stage that pays the most Wins a minute, or the stage you pick. |
| 👑 | **Bosses** | Beats each world's boss for a Boss Chest every clear. Pick a boss or let it choose. |
| 🕳️ | **Depths** | The Infinite Depths, floor after floor, with the best power card picked after each. Boss floors pay Mutagen. Leave at a floor if you like. |

## What it does
- **Trains** on the best sound pad you own, in every world.
- **Fights** the strongest stage it can win, then it **collects the win**. It **evolves** the moment it can, in every mode.
- **Every world and every strain the game has**: right now Worlds 1-4 (Stages 1-60) up to the last strain (Usurper).
- **Ready for game updates:** worlds, world bosses, stages, strains and new abilities are read from the game each time it starts, so a new world or strain needs no new script.
- **Double Wins:** if you own the pass, it uses the 2× win pad. It never touches a Robux pad otherwise.
- **Smart bosses:** it breaks the shield towers first, dodges stuns, slams and grabs, and stands behind enemies. A boss too big for you yet (like Stage 58's Fossil Wyrm) is set aside until you're strong enough, instead of eating five minutes a try.
- **Traps:** it keeps clear of the map's traps and stands on an invisible platform at edges, so you don't fall off.
- **Combo moves** and **your abilities** in every fight.
- **Free rewards:** the daily reward, playtime gifts, and finished daily, weekly and story quests.
- **Chests:** opens Boss, Mega and Halloween chests and skips their animations. It also skips cutscenes.
- **Kill aura and instant kill** (off by default, at your own risk). Range goes up to the whole fight, it breaks shield towers in one hit, and it can **hide you under the floor** while it fights. It stays under the server's hit limits unless you switch that off. Big bosses still take real hits: the server cuts any hit past about 13× your strength.
- **Your own Discord webhook:** posts your items, currencies and what the farm is doing.
- **Bug report and idea boxes**, and an **Updates** tab.

## Spending
- **Never Robux.**
- Ability Tokens, Mutagen (altar spins) and potions are only spent if you switch them on. Every spend is listed in the Farm tab.

## Good to know
- Right Shift shows or hides the window. After a reload it starts hidden.
- Your settings and what it learns are saved in `VE_SmartFarm/` in your executor's workspace.
