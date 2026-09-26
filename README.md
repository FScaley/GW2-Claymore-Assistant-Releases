# Claymore Law Assistant

An in-game assistant for Guild Wars 2, as a [Nexus](https://raidcore.gg/Nexus) addon: **Next Steps**, which tells you what to do next from your own account, and an AI chat powered by Google Gemini.

## Next Steps

Press **ALT+N** (or right-click the Claymore icon) to open it. With your GW2 API key it reads your account - story, masteries, mounts, elite specializations, gear, fractals, raids, legendaries and more - and suggests the next three steps, from a new account to the endgame, each with the reason it was picked. The decisions are made by fixed rules, not by the AI; it needs no Gemini key.

- **Next:** the top three steps, with the time they take, where they are, Find on Map, Show (the markers of your packs, with [Claymore Law Pathing](https://github.com/FScaley/GW2-CL-Pathing-Releases)) and the wiki page; snooze, hide or mark a step done. What is locked or could not be checked says why.
- **Gear:** what is off with the equipment of the character you play - empty slots, low-level or low-rarity items, empty rune / sigil / infusion slots, a weapon whose skills are greyed out - as problems, warnings and advice.
- **Goals:** the goals closest to you (legendaries, all mounts, a region's mastery points...) and up to three you track.
- **Roadmap:** everything, searchable. **Settings:** what you like, the content the API cannot see that you own.

Your account is read only while the window is open (the GW2 API can be 5-60 minutes behind the game). The key needs the permissions account, progression, characters, unlocks, inventories, wallet, builds and pvp.

## Chat

Ask about NPCs and locations, crafting recipes, Trading Post prices, waypoints, builds and general game questions. It answers from the GW2 Wiki, community guides, metabattle builds and the GW2 API.

Its **Find on Map** panel, beside the chat window, finds NPCs and places, achievements and marker-pack categories; [Claymore Law Pathing](https://github.com/FScaley/GW2-CL-Pathing-Releases) (v0.7.0 or newer) shows them in the game and on the world map, and can lead you through them step by step.

## Installation

1. [Nexus](https://raidcore.gg/Nexus) must be installed.
2. Download `claymore-assistant.dll` from the [latest release](../../releases/latest) and put it in the game's `addons/` folder (or install it from Nexus).
3. In the Nexus options (CTRL+O > Addons > Claymore Law Assistant), enter your GW2 API key (for Next Steps and questions about your account) and, for the chat, your own Gemini API key.
4. In the game, press **ALT+N** for Next Steps and **ALT+C** for the chat window.

Updates arrive automatically through Nexus.

### Upgrading from "Claymore Law Asistan" (v0.5.x)

The addon was renamed in v0.6.0 and the old version does not update to it automatically. Install `claymore-assistant.dll` as above and **delete `claymore-asistan.dll`** from the `addons/` folder (both can't be loaded at the same time). Your settings, API keys and chat history move over on the first start.

## Language

English by default. Turkish is available in the options (**Language / Dil**); the assistant then answers in Turkish.

## Note

This repository only distributes releases (the DLL). Please use [Issues](../../issues) for bug reports.

## Legal

Guild Wars Games (c) ArenaNet LLC. All rights reserved. NCSOFT, ArenaNet, Guild Wars, Guild Wars 2, GW2, Heart of Thorns, Path of Fire, End of Dragons, Secrets of the Obscure, Janthir Wilds, Visions of Eternity, and all associated logos, designs, and composite marks are trademarks or registered trademarks of NCSOFT Corporation. All other trademarks are the property of their respective owners.
