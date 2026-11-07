<p align="center">
  <a href="https://robbyczesany.com"><img src="assets/banner.svg" alt="Robby Czesany · Agentic engineer. I build pocket-ui, a cozy frontend for retro handhelds, and tools for Hermes Agent." width="100%"></a>
</p>

<p align="center">
  <a href="https://robbyczesany.com"><img alt="robbyczesany.com" src="https://img.shields.io/badge/robbyczesany.com-090d0c?style=flat-square"></a>
  <a href="https://websearchplus.xyz"><img alt="websearchplus.xyz" src="https://img.shields.io/badge/websearchplus.xyz-070d0c?style=flat-square"></a>
  <a href="https://activityplus.xyz"><img alt="activityplus.xyz" src="https://img.shields.io/badge/activityplus.xyz-070d0c?style=flat-square"></a>
  <a href="https://hermesui.xyz"><img alt="hermesui.xyz" src="https://img.shields.io/badge/hermesui.xyz-070d0c?style=flat-square"></a>
  <a href="https://pocketui.xyz"><img alt="pocketui.xyz" src="https://img.shields.io/badge/pocketui.xyz-070d0c?style=flat-square"></a>
  <a href="mailto:robby@robbyczesany.com"><img alt="robby@robbyczesany.com" src="https://img.shields.io/badge/robby@robbyczesany.com-090d0c?style=flat-square"></a>
</p>

| **442★** | **88k+** | **14** |
| :-- | :-- | :-- |
| web-search-plus for Hermes | ClawHub skill downloads (2026-11-07) | handhelds supported by `pocket-ui` |

I build `pocket-ui`, a cozy frontend with its own player for retro handhelds, and tools for [Hermes Agent](https://github.com/NousResearch/hermes-agent): Web Search Plus, the HUI+ app and HUI+ Cards. Plus Activity+, which tells you what your Mac and phone are really doing.

## Main projects

### 🎮 [`pocket-ui`](https://pocketui.xyz)

<a href="https://pocketui.xyz"><img src="https://raw.githubusercontent.com/robbyczgw-cla/pocket-ui/main/docs/media/hero.webp" alt="The pocket-ui shelf: Advance Wars ready to continue, the last games as cases and every console as a spine" width="560"></a>

**A cozy frontend with its own player for retro handhelds.** Free and open source (GPLv2, Rust), no account, no ads, no tracking.

- **Every game in its real box.** One shelf, press A and you are playing, right where you left off. One pause menu from Game Boy to GameCube, with saves that come with pictures.
- **14 handhelds, with [ROCKNIX](https://rocknix.org).** Retroid Pocket (Mini V2, Mini, 5, 6, Flip 2, Nova), AYN Odin 2 (Mini, Odin 2, Portal), Anbernic (RG35XX, RG40XX, RG34XX, RG28XX, RG-SP).
- **Easy to live with.** Send games from your phone with a QR code; Wi-Fi updates keep your games and saves. Next: 0.3 with a Retro look, and TrimUI Brick support is coming.

→ [pocketui.xyz](https://pocketui.xyz) · [pocket-ui](https://github.com/robbyczgw-cla/pocket-ui) · [0.2.4 release](https://github.com/robbyczgw-cla/pocket-ui/releases/tag/v0.2.4)

### 🧩 [Hermes](https://github.com/NousResearch/hermes-agent)

<a href="https://hermesui.xyz"><img src="https://raw.githubusercontent.com/robbyczgw-cla/hermes-ui-plus/main/docs/images/hero.jpg" alt="HUI+ on a phone: an approval card shows the command Hermes wants to run, its reason and an estimated risk, with Allow once, For this task, Always allow and Deny" width="560"></a>

**Search with sources, an app you act in, and answer cards for Hermes Agent.** Open source, MIT.

- **[Web Search Plus](https://websearchplus.xyz)** 5.1.7, 442★. The original links and the cleaned page, never a generated answer, with a receipt for every source. 15 search and 9 extract providers; also runs in Grok Build (submitted), NanoClaw, OpenClaw and any MCP client.
- **[HUI+ · Hermes UI+](https://hermesui.xyz)** 0.3.1, alpha. A chat app for your own Hermes on Android, web (PWA), macOS and Linux: tick, choose, compare and approve right inside the answer. Unofficial.
- **[HUI+ Cards](https://github.com/robbyczgw-cla/hermes-ui-cards)** 0.1.0, new today. Hermes asks with a card, you tap, your answer is the next message. 17 card types, Desktop and Webapp, text fallback elsewhere. Needs Hermes 0.22.6 or newer.

```bash
hermes plugins install web-search-plus --enable                       # Hermes, official plugin catalog
hermes plugins install robbyczgw-cla/hermes-ui-cards --enable         # answer cards
uvx --from web-search-plus-mcp==5.1.6 web-search-plus-mcp             # Web Search Plus for any MCP client
```

→ [hermes-web-search-plus](https://github.com/robbyczgw-cla/hermes-web-search-plus) · [web-search-plus-mcp](https://github.com/robbyczgw-cla/web-search-plus-mcp) · [OpenClaw plugin](https://github.com/robbyczgw-cla/web-search-plus-plugin) · [NanoClaw](https://github.com/robbyczgw-cla/nanoclaw-web-search-plus) · [hermes-ui-plus](https://github.com/robbyczgw-cla/hermes-ui-plus) · [hermes-ui-cards](https://github.com/robbyczgw-cla/hermes-ui-cards)

## More work

### 📊 [Activity+](https://activityplus.xyz) · flagship

A system monitor that names the app responsible, keeps 30 days of history and answers "why is my Mac slow?" with a finding and a fix button. Agents get the same data through a read-only MCP server with 19 tools. Mac: Swift, MIT, notarized, `brew install robbyczgw-cla/tap/activity-plus`. No account, no analytics.

**Android** tells you which app drains the battery or keeps the phone awake at night. 0.6.4 (7 Nov) makes "who woke the phone" work on phones with hundreds of apps and leaves out impossible battery values from odd phones; the card says how many apps are missing. No internet permission.

→ [Mac 0.5.0](https://github.com/robbyczgw-cla/activity-plus/releases/tag/v0.5.0) · [Android 0.6.4](https://github.com/robbyczgw-cla/activity-plus-android/releases/tag/v0.6.4) · [activity-plus](https://github.com/robbyczgw-cla/activity-plus) · [activity-plus-android](https://github.com/robbyczgw-cla/activity-plus-android) · [1-minute film](https://activityplus.xyz/assets/video/activityplus-trailer.mp4)

### 🌙 Skills

Skills that watch, remember and propose. Nothing lands until you approve it.

| Skill | What it does |
| :-- | :-- |
| [lucid-dreamer](https://clawhub.ai/robbyczgw-cla/lucid-dreamer) | Reviews agent memory every night, finds patterns, proposes changes |
| [skillminer](https://clawhub.ai/robbyczgw-cla/skillminer) | Finds work that keeps repeating and drafts a skill for it; never activates itself |
| [topic-monitor](https://clawhub.ai/robbyczgw-cla/topic-monitor) | Watches topics on a schedule and scores each item; in [DigitalOcean's OpenClaw skills guide](https://www.digitalocean.com/resources/articles/what-are-openclaw-skills) |
| [roundtable](https://clawhub.ai/robbyczgw-cla/roundtable) | Runs three agents in parallel and makes them cross-examine each other |

Also: [personas](https://github.com/robbyczgw-cla/clawdbot-personas), [agent-chronicle](https://clawhub.ai/robbyczgw-cla/agent-chronicle), [OpenCami](https://github.com/robbyczgw-cla/opencami) (web client for OpenClaw).

## Upstream

- **Nous Research:** web-search-plus in the [Hermes plugin catalog](https://hermes-agent.nousresearch.com/docs/plugins); co-author of the [prompt-cache fix](https://github.com/NousResearch/hermes-plugin-claude-subscription-directsdk/commit/d032bed) in the Claude subscription plugin
- **OpenClaw:** 19 merged PRs in core: Telegram, Discord, sessions, formatting, OpenRouter thinking
- **Lists:** [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills), [awesome-hermes-agent](https://github.com/0xNyk/awesome-hermes-agent)

## Now

- **Mac** · Activity+ 0.5.0
- **Android** · Activity+ 0.6.4
- **Handheld** · [`pocket-ui`](https://pocketui.xyz) 0.2.4
- **Agents** · Web Search Plus 5.1 (442★)
- **Hermes** · HUI+ 0.3.1 and HUI+ Cards 0.1.0 (first release today)

**Stack:** Go · Python · TypeScript · React / React Native · Tauri · Node · Vite · Expo · SQLite · Docker / Colima · MCP

<sub>Graz, Austria (CET) · open to agent-infrastructure work: robby@robbyczesany.com</sub>
