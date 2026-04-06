# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Custom in-universe epilogues for a **Clank! Legacy: Acquisitions Incorporated** campaign. Each session produces a field report in two formats: a Markdown source file (`gameN.md`) and a styled HTML version (`gameN-html.html`). Reports are written as Acquisitions Incorporated corporate documents — dry bureaucratic humor, fantasy adventure, character-driven narrative.

## Reference Materials

- `resources/40-clank-legacy-acquisitions-incorporated-rulebook.pdf` — game mechanics (knockouts, Danger Zone, artifacts, scoring, contracts)
- `resources/ClankLegacy_Book_Of_Secrets.pdf` — all numbered passages (1–189) for the campaign story

**NEVER reveal story content from the Book of Secrets unprompted.** Only reference passages the user has already played through. When confirming a passage, be vague about its content: "Passage 41 involves an abandoned location — does that sound right?" Never describe what happens in unplayed passages.

## Critical Language Rules

Avoid board game terminology — use in-universe equivalents:
- "mission" not "game"
- "hired sword" not "card purchase"
- "tireless legs" not "Boots"
- "knocked out" not "killed" or "dead" — characters return next mission
- "knocked out above the Danger Zone" = still earns rewards; "knocked out in the Danger Zone" = nothing to show

In-universe terms that ARE correct: Seals of Excellence, Contracts, Dran Enterprises, Associate Spotlight.

## Tone & Style

- Filed by "Regional Oversight on behalf of the field team"
- Dry corporate humor mixed with fantasy adventure
- Home Office Notes: short paragraphs, corporate voice, dark humor — the punchiest section
- Ends with "Come Back Next Mission For:" mirroring the Book of Secrets epilogue format
- Reports should be roughly similar in length to Game 1 (tight and punchy)

## HTML Style

- Parchment aesthetic: warm background gradient (`#f4e4c1` to `#e5d0a0`), dark border (`#8b7355`)
- Fonts: Cinzel (headings), Crimson Text (body) — loaded from Google Fonts
- Section titles: uppercase, letter-spaced, with bottom border
- Dividers: `— ◆ —` between major sections
- Home Office Notes: indented block with left border, italic
- Dark outer background (`#1a1410`) framing the parchment
- Single continuous scroll — no page breaks (for mobile sharing)

## Characters

| Character | Archetype | Running joke / trait |
|-----------|-----------|----------------------|
| **Harry** | The schemer | "He's a wizard." Strategic information withholder. Canoe inventor. |
| **Sir Prize** | The tragic hero | Noble to a fault — literally. Two braids that question the "Sir." |
| **Bonkbeard** | The underdog | Dwarf with hammer and beard. Terrible luck until suddenly not. |
| **Piko** | The wildcard | Tiny goblin/gnome. Fearless, enthusiastic, forgets critical things at worst moments. |

**Franchise:** The Drunken Dragon | **Town:** Wondelcreek

## Key NPCs

- **Duke Destrin** — Nobleman, wants ancestral dwarven sword, says "so long as they remain loyal"
- **Vriz** — Duke's wizard advisor, requests mystic fruit, has a cabin in the mushroom forest
- **Garji** — President, Greater Ridge Area Explorers Society (met Bonkbeard, Passage 8)
- **Mayor Schroeder** — Mayor of Wondelcreek, loves pie, loves The Drunken Dragon
- **Malathrex** — The dragon. Found Bonkbeard boring in Game 2.
- **Portentia Dran** — Omin's evil sibling, runs Dran Enterprises, growing threat
- **Omin Dran** — CEO of Acquisitions Incorporated, signs Home Office Notes
- **Barry Batsbal** — Companion card named by Sir Prize in Game 2; provided third Seal of Excellence

## Campaign State Heading Into Game 3

**Dran Enterprises Track:** Two X marks (Sir Prize Danger Zone knockout + unexplored northern tunnels)

**Unresolved threads:**
- Cauldron contract from Passage 9 (Piko, Game 1) — still unfulfilled after two missions
- Path sticker from Passage 8 never placed (Bonkbeard, Game 1)
- Northern secret tunnels (contracted Game 1) — never explored

**Running themes to carry forward:**
- "Strategic Information Withdrawal" — Harry withheld Game 1 win; teammates guided Sir Prize to fatal detour; Piko forgot pickaxes
- The Mountains — claimed victims two missions running (Bonkbeard barely survived G1, Sir Prize zero-pointed G2)
- The Canoe — Harry's G1 signature move, stolen by Bonkbeard in G2
- Sir Prize's Tragedy — Associate Spotlight in G1 → zero points in G2
- Bonkbeard's Redemption — last place in G1 → MVP in G2
- The Cauldron Woman — patience wearing thin

## When Starting a New Session Report

Ask the user for: character actions, waypoint/passage numbers visited, key choices made, scores/placements, memorable moments. Do NOT list or describe passage content when asking — let the user describe events in their own words.
