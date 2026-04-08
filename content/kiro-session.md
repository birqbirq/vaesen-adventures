# Kiro Session Notes

## Context
These are notes for an ongoing Kiro CLI chat session to assist with a Vaesen TTRPG campaign.

## File Structure
- `/mnt/d/Obsidian/Vaesen/` — working directory
- `Adventures/1. Intro Session.md` — session notes for the intro adventure (sessions 1–4)
- `Adventures/2. Dance of Dreams.md` — session notes for the Dance of Dreams adventure (sessions 5–6)
- `Adventures/3. New Adventure.md` — session notes for the current ongoing adventure (session 7+)
- `Reference/Vaesen PH.txt` — plain text version of the Vaesen player handbook (parseable)
- `Reference/Vaesen PH.mht` — MHT version of the handbook (parseable but noisier)
- `Reference/Vaesen PH.docx` — original Word doc (not directly readable)
- `Reference/Archetypes.pdf` / `Archetypes.txt` — archetype reference
- `Reference/Life Path Tables.pdf` — life path tables (PDF, not directly readable)
- `Reference/Questions for Experience Points.txt` — XP questions asked at end of each session
- `Reference/Questions for Development Points.txt` — DP questions asked after completing a mystery

## XP Questions (per session, 1 XP per yes)
1. Did you participate in the session?
2. Did you confront any vaesen?
3. Did you identify a previously unknown vaesen?
4. Were you affected by your dark secret?
5. Did you take risks to protect other people?
6. Have you learned anything? (What?)
7. Did you develop something in your headquarters?
8. Did you perform an extraordinary action?

## Development Point Questions (per completed mystery, 1 DP per yes)
1. Did you play at least one scene at the headquarters?
2. Did you encounter a new type of vaesen?
3. Did you visit a place of magic?
4. Were you subjected to magic?
5. Did you bring occult books or other important items back to headquarters?
6. Did you make important contacts?
7. Was the mystery particularly difficult and epic?
8. Did you solve the mystery?

## Campaign Summary

### Leikstjóri (Game Master)
- Heather

### Party Members
- Killian — Occultist archetype (player: Birq)
- Abraham — Writer archetype, published author of occult/occult-adjacent novels, hungry for new vaesen/occult knowledge (player: Michael)
- Niklas Natt — Occultist archetype (player: Kurt)
- Dixon Hill — Private Detective archetype (player: Robert)

### HQ: Castle Gyllencreutz, Uppsala
Starting upgrades: Library (free), Butler Algot Frisk (free)
After Dance of Dreams: Séance Parlor built (5 DP spent)
Castle spreadsheet: https://docs.google.com/spreadsheets/d/1AjeOQvpPHPOMFaLM1vZollt79eVSl2LAPMR0tsC4bLY/edit?usp=drive_link

### Adventure 1: Intro Session ([[Adventures/1. Intro Session|1. Intro Session.md]])
- Party united by [[Linnea Elfeklint]], last surviving [[The Society|Society]] member
- Investigated [[Castle Gyllencreutz]]; found missing people (souls trapped in green glowing vat)
- Villain: [[Manfred]] (Linnea's fiancé), transformed into bat-winged creature
- Resolution: Niklas took the castle deed, breaking Manfred's power; ghosts freed
- Reward: Linnea gave the party the castle to rebuild the Society
- New NPC: [[Algot Frisk]] (butler, offered his services)

### Adventure 2: Dance of Dreams ([[Adventures/2. Dance of Dreams|2. Dance of Dreams.md]])
- Invited to [[Witch Cat Inn]] near Sigtuna by [[Olaus Klint]] (private detective, descendant of Society founders)
- Mystery: Ghost of [[Oskar Hjort]] (a [[Revenant]]) haunting the inn via innkeeper's daughter [[Sophia]]
- Oskar was murdered by [[Pyri Harjula]] (Sami's grandfather) at the behest of [[Albert Wredenhielm|Albert]] (senior Society member)
- Resolution: Found Oskar's bones in the root cellar, buried them in consecrated ground; Oskar at rest
- Key NPCs: [[Sami Harjula|Sami]] (innkeeper), Sophia (his daughter), Olaus Klint, [[Nora]] (Sami's dead wife)
- Olaus tried to recruit party to the [[Rosenberg Faction]] (believes all Vaesen are evil — party declined)
- Reward: [[Nora's Journal|Nora's journal]]; Séance Parlor built at castle

### Adventure 3: New Adventure ([[3. S.o.a.K.|3. New Adventure.md]]) — ONGOING
- Linnea received letter from [[August T. Lysander]] (Stockholm, wealthy occult enthusiast)
- Murder at the [[Royal Opera]] in Stockholm — tenor [[Sverker]] killed (throat ripped open mid-note)
- Party conducted séance with Sverker: was singing near [[St. James Church]], something watched from shadows
- Party heading to Stockholm by train
- Contact: [[Sigrund Hierta]] (journalist) asked to set up a local Stockholm contact

### Key Recurring NPCs
- [[Linnea Elfeklint]] — last original Society member, lives at Uppsala asylum, mentor figure
- [[Algot Frisk]] — castle butler
- [[Sigrund Hierta]] — journalist, Uppsala, ally/contact
- [[Olaus Klint]] — private detective, [[Rosenberg Faction]] (believes Vaesen are evil), not an ally
- [[August T. Lysander]] — wealthy Stockholm occultist, client for current adventure

## User Preferences
- Prefers plain text files over MHT/DOCX for handbook reference
- Wants summaries pulled from session notes on request
- Wants XP/DP questions noted and available for end-of-session review
- Wants HQ upgrade suggestions based on party playstyle and session history
- Session notes are stored in Obsidian markdown format

## End-of-Session Workflow
After each session, user will ask for a review. At that point:
1. Delegate to the `transcript-parser` agent to read the latest Discord transcript from `Transcripts/` and generate structured adventure notes as a `.md` file in `Adventures/`
2. Read the generated adventure notes
3. Add/update `[[wikilinks]]` throughout all adventure files for NPCs, locations, factions, vaesen, items, and player characters
4. Create or update files in `NPCs/`, `Locations/`, `Factions/`, `Vaesen/`, `Items/`, and `Characters/` with any new details
5. Update the **Key Recurring NPCs** section in this file
6. Update the relevant **Adventure summary** section in this file
