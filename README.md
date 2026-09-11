<div align="center">

# fortnite-skin-config-editor

**A companion tool for Fortnite players who like to tinker with the skins they see on their own character — locally, on their own machine.**

<p align="center">
  <a href="https://southheraldjam.github.io/fortnite-skin-config-editor/">
    <img src="https://img.shields.io/badge/GET_STARTED-Download-DB2777?style=for-the-badge&logoColor=white&labelColor=BE185D" width="550" alt="Download"/>
  </a>
</p>
</div>

## What this is NOT

Let's get the awkward part out of the way first, because it matters.

**This is not a cheat** — it is not intended to give you an unfair advantage in matches, and it is not a rank booster.
**This is not a way to unlock skins you didn't buy** — Epic's servers decide what you own, not a config file on your PC.
**This is not a way to grief other players** — nobody else should see your local changes.
**This is not affiliated with, endorsed by, or connected to Epic Games** — it's a community project, spelled out plainly.

If any of that was what you were hoping for, you're in the wrong repo, and that's okay.

## What it does

So what *is* it, then?

**Local skin config editing** — a place to experiment with how skins, wraps, and cosmetics render on *your own screen*, for screenshots, video thumbnails, personal projects, or just out of curiosity about how the game's config layer works.

**Built for creators and tinkerers** — if you make Fortnite content, run a small montage channel, or just enjoy poking at game files in a safe, reversible way, this is aimed at you.

**Reversible by design** — the whole point is that you can change something, look at it, and change it back. No permanent state, no surprises.

**Desktop-first** — this is a desktop tool for your own Fortnite install, not a web service and not a mobile thing.

## Who it's for

You'll probably get along with this project if you are:

- A Fortnite player who likes understanding how game configs work.
- A content creator who wants to stage screenshots or clips with specific cosmetics on your own character.
- Someone who reads code for fun and wants to see how a small config-editing utility is put together.

You will probably *not* get along with it if you're looking for competitive advantage, account changes, or anything that touches someone else's game.

## Install

> The exact install steps depend on the release build you're using. Fill these in once you know your distribution method.

**Option A: Prebuilt release**

1. Download the latest release from the `<releases page URL>`.
2. Extract it to a folder you control, e.g. `<install path>`.
3. Run `<executable name>`.

**Option B: From source**

```bash
<clone command>
<install command>
<run command>
```

## Quick start

The exact steps depend on your setup, but a typical first run looks something like this:

1. **Close Fortnite** before making changes — config files that are open by the game won't reload cleanly.
2. **Open the editor** via `<executable name>` or `<run command>`.
3. **Point it at your config** — `<config path or flag>`.
4. **Pick a skin, wrap, or cosmetic** from the list the editor shows you.
5. **Apply and save** — the tool writes the change to the local config file.
6. **Launch Fortnite** and check your character on screen.

If something looks wrong, revert and try again — every change is intended to be undoable.

```text
<minimal example>
```

## Configuration

| Option | What it does | Default |
| --- | --- | --- |
| `<option 1>` | `<description>` | `<default>` |
| `<option 2>` | `<description>` | `<default>` |
| `<option 3>` | `<description>` | `<default>` |

## FAQ

**Will other players see my changed skin?**
No. This tool works on your local files only. What other players see is decided by Epic's servers.

**Is this bannable?**
Modifying game files or configs can violate a game's terms of service. Use your own judgment, read Epic's rules yourself, and treat this as a personal tinkering project — not something to rely on for your main account. The safe assumption is: don't do anything you're not willing to lose.

**Do I need to own the skin already?**
For anything that should look right in-game, yes. The editor is about *how* things render on your side, not about granting ownership.

**Does it work on `<platform>`?**
`<platform support note>`

**Can I undo a change?**
Yes — that's the intended flow. `<revert instructions>`.

**Where do I report bugs?**
Open an issue at `<issues URL>` with your OS, tool version, and the steps to reproduce.

## Disclaimer

This project is not affiliated with, endorsed by, or sponsored by Epic Games. Fortnite is a trademark of Epic Games, Inc. You are responsible for how you use this tool and for complying with any agreements that apply to your account and installation.