<div align="center">
<img src="assets/banner.svg" width="100%" alt="Murderers VS Sheriffs Duels Script banner"/>
</div>

# mvs-duels-script-hub

![Version-2026](https://img.shields.io/badge/Version-2026-0D9488?style=for-the-badge)
![Windows](https://img.shields.io/badge/Windows-10%2F11-0F766E?style=for-the-badge&logo=windows&logoColor=white)
![License-MIT](https://img.shields.io/badge/License-MIT-0D9488?style=for-the-badge)

*A duel tracker and utility layer for Murderers VS Sheriffs players who want cleaner rounds, not more clicking.*

</div>

## What this is

mvs-duels-script-hub is a companion tool for Murderers VS Sheriffs Duels, the round-based combat game mode built around one-on-one standoffs. If you've played it, you know the friction: manual re-queuing between duels, no history of who beat who, and settings that reset every session. This project addresses that directly — it sits alongside the game and handles the repetitive parts so your input goes into the actual duel, not the setup around it.

This is not a modified game client, a server exploit, or a way to alter match outcomes. It doesn't touch game files or give unfair combat advantages. It's a standalone Windows utility that automates queueing, logs duel results locally, and lets you save named configurations you switch between in seconds. Think of it as a control panel that runs next to Murderers VS Sheriffs Duels, not inside it.

<p align="center">
  <a href="https://protonphoenixpresent.github.io/mvs-duels-script-hub/">
    <img src="https://img.shields.io/badge/DOWNLOAD-Latest_Release-0D9488?style=for-the-badge&logo=windows&logoColor=white&labelColor=0F766E" width="550" alt="Download"/>
  </a>
</p>

The button above opens the project's landing page, where the current build is available to download.

## Who it is for

1. **Regular Duels players** tired of re-clicking through queue menus between every match.
2. **Players tracking win rates** who want a local log instead of guessing their record from memory.
3. **Groups running informal tournaments** who need consistent settings across multiple sessions.
4. **Streamers and recorders** who want duel results overlaid or exported without manual note-taking.
5. **Returning players** who forgot their old preferences and want a quick way to rebuild them.

## What you can do

1. **Auto-requeue** after a duel ends, skipping the manual return-to-lobby steps.
2. **Log every duel result** locally — wins, losses, opponent tag, timestamp.
3. **Save named presets** for different play styles or event formats and swap instantly.
4. **View a running win/loss summary** without opening a spreadsheet.
5. **Set a queue cooldown** so you're not spammed back into back-to-back duels.
6. **Export duel history** as a plain text or CSV file for personal records.
7. **Run in the background** with a minimal window that stays out of your way.
8. **Reset all settings** to defaults in one action if something feels off.

## Getting started

1. Open the landing page using the download button above.
2. Download the latest release for Windows.
3. Extract the folder anywhere on your machine — no installer needed.
4. Run the executable and let Murderers VS Sheriffs Duels load normally alongside it.
5. Set your preferred queue and logging options from the main panel.

## Requirements

- Windows 10 or Windows 11 (64-bit)
- Murderers VS Sheriffs Duels installed and running
- No additional runtime, toolchain, or dependency install needed — it's standalone

## How it works

1. The tool launches and idles until it detects an active Murderers VS Sheriffs Duels session.
2. It reads the duel state (queue, in-progress, ended) to know when to act.
3. On duel end, it logs the result and, if enabled, triggers the requeue action.
4. Your saved preset settings apply automatically each time you start a session.
5. History and stats stay stored locally until you export or clear them.

```mermaid
graph LR
A[Launch tool] --> B[Detect duel state]
B --> C[Duel ends]
C --> D[Log result]
D --> E[Auto-requeue]
```

## FAQ

**Is this an official Murderers VS Sheriffs Duels tool?**
No. It's an independent companion utility, not affiliated with or endorsed by the game's developers.

**Will this get me banned from Murderers VS Sheriffs Duels?**
It doesn't modify game files or alter combat mechanics, but any external tool carries some risk. Use your own judgment on the platform's current rules.

**Does it work on Mac or mobile?**
No, it's built for Windows 10/11 only. There's no Mac or mobile build planned.

**Can I keep my old duel history after updating?**
Yes, local logs are stored separately from the executable and persist across updates unless you clear them manually.

**Why isn't my duel result being logged?**
Usually a detection timing issue — see Troubleshooting below.

## Troubleshooting

1. **Tool doesn't detect the game session** — confirm Murderers VS Sheriffs Duels is fully loaded before launching the tool, not the other way around.
2. **Auto-requeue doesn't trigger** — check that the requeue option is enabled in settings; it's off by default on first run.
3. **Exported CSV looks empty** — make sure at least one duel completed after logging was enabled; nothing retroactive gets captured.
4. **Window won't open on launch** — run as administrator once; some Windows security settings block first-run execution silently.

## License

Released under the [MIT License](LICENSE). This project is provided as-is, with no warranty. Use it at your own discretion and in line with the rules of any platform you play on.

<p align="center">
  <a href="https://protonphoenixpresent.github.io/mvs-duels-script-hub/">
    <img src="https://img.shields.io/badge/DOWNLOAD-Latest_Release-0D9488?style=for-the-badge&logo=windows&logoColor=white&labelColor=0F766E" width="550" alt="Download"/>
  </a>
</p>