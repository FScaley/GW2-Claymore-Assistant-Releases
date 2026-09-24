# Claymore Law Assistant

An in-game AI chat assistant for Guild Wars 2, as a [Nexus](https://raidcore.gg/Nexus) addon, powered by Google Gemini.

Ask about NPCs and locations, crafting recipes, Trading Post prices, waypoints, builds and general game questions. It answers from the GW2 Wiki, community guides, metabattle builds and the GW2 API.

Its **Find on Map** panel, beside the chat window, finds NPCs and places, achievements and marker-pack categories; [Claymore Law Pathing](https://github.com/FScaley/GW2-CL-Pathing-Releases) (v0.7.0 or newer) shows them in the game and on the world map, and can lead you through them step by step.

## Installation

1. [Nexus](https://raidcore.gg/Nexus) must be installed.
2. Download `claymore-assistant.dll` from the [latest release](../../releases/latest) and put it in the game's `addons/` folder (or install it from Nexus).
3. In the game, press **ALT+C** to open the chat window.
4. In the Nexus options (CTRL+O > Addons > Claymore Law Assistant), enter your own Gemini API key. A GW2 API key is optional, for questions about your own account.

Updates arrive automatically through Nexus.

### Upgrading from "Claymore Law Asistan" (v0.5.x)

The addon was renamed in v0.6.0 and the old version does not update to it automatically. Install `claymore-assistant.dll` as above and **delete `claymore-asistan.dll`** from the `addons/` folder (both can't be loaded at the same time). Your settings, API keys and chat history move over on the first start.

## Language

English by default. Turkish is available in the options (**Language / Dil**); the assistant then answers in Turkish.

## Note

This repository only distributes releases (the DLL). Please use [Issues](../../issues) for bug reports.
