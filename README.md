# ◓ ChampLog

**Battle logger, replay viewer, and win-rate stats for Pokémon Champions.**

Pokémon Champions has no replay feature — ChampLog is the companion app that fixes that without touching the game. Log battles in about a minute (or let it auto-scan your screen recording), then step through replays turn by turn and see which leads actually win you games.

**▶ Use it / install it: https://kimtantakorn.github.io/champlog/**

## Features

- ⚡ **Quick logging** — tap side → Pokémon → action (Move / Switch / KO / Status / Note), turn by turn
- 🎬 **Auto-scan** — attach an iOS/Android screen recording of your battle; ChampLog frame-diffs the battle-text region and finds every moment for you to label (pure pixel math, no AI/ML)
- ⏪ **Replay viewer** — scrub any battle turn by turn, KO'd Pokémon crossed out as it unfolds; with a recording attached, tap any event to jump the video to that moment
- 📊 **Stats** — overall win rate, win rate **by lead**, most-fainted, most-KO'd
- 📱 **Installs like an app** — Add to Home Screen on iPhone/iPad/Android; works offline
- 🔒 **Your data stays on your device** — localStorage only, with JSON export/import for backup

## Install on your phone

- **iPhone / iPad**: open the link in Safari → Share → **Add to Home Screen**
- **Android**: open in Chrome → ⋮ → **Add to Home screen**

## Tech

One HTML file. No framework, no build step, no server, no AI. Vanilla JS + Canvas frame-differencing for the video scan. Part of the **VibeBuild** 100-projects series — [@vibebuildhq](https://github.com/KimTantakorn).

## License

**PolyForm Noncommercial 1.0.0** — free for personal and educational use. Commercial use requires a paid license: see [COMMERCIAL.md](COMMERCIAL.md).

© VibeBuild (K.T.). Not affiliated with Nintendo, The Pokémon Company, or Pokémon Works. Pokémon is a trademark of Nintendo / Creatures Inc. / GAME FREAK inc.
