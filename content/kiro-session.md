# Kiro Session Notes

## Context
These are notes for an ongoing Kiro CLI chat session to assist with a Vaesen TTRPG campaign.

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

### Adventure 1: Intro Session ([[1 - Intro Session|1. Intro Session.md]])
- Party united by [[Linnea Elfeklint]], last surviving [[The Society|Society]] member
- Investigated [[Castle Gyllencreutz]]; found missing people (souls trapped in green glowing vat)
- Villain: [[Manfred]] (Linnea's fiancé), transformed into bat-winged creature
- Resolution: Niklas took the castle deed, breaking Manfred's power; ghosts freed
- Reward: Linnea gave the party the castle to rebuild the Society
- New NPC: [[Algot Frisk]] (butler, offered his services)

### Adventure 2: Dance of Dreams ([[2 - Dance of Dreams|2. Dance of Dreams.md]])
- Invited to [[Witch Cat Inn]] near Sigtuna by [[Olaus Klint]] (private detective, descendant of Society founders)
- Mystery: Ghost of [[Oskar Hjort]] (a [[Revenant]]) haunting the inn via innkeeper's daughter [[Sophia]]
- Oskar was murdered by [[Pyri Harjula]] (Sami's grandfather) at the behest of [[Albert Wredenhielm|Albert]] (senior Society member)
- Resolution: Found Oskar's bones in the root cellar, buried them in consecrated ground; Oskar at rest
- Key NPCs: [[Sami Harjula|Sami]] (innkeeper), Sophia (his daughter), Olaus Klint, [[Nora]] (Sami's dead wife)
- Olaus tried to recruit party to the [[Rosenberg Faction]] (believes all Vaesen are evil — party declined)
- Reward: [[Nora's Journal|Nora's journal]]; Séance Parlor built at castle

### Adventure 3: A Stranger in Stockholm ([[3 - S.o.a.K.|S.o.a.K.]]) — ONGOING
- Client: [[August T. Lysander]] (wealthy Stockholm occultist) — believes a vaesen killed tenor [[Sverker]] von Essen at the [[Royal Opera]]
- Séance with Sverker: something watched him from shadows near [[St. James Church]] as he sang; throat ripped open mid-note
- Conductor [[Mortimer Cronstedt]] also dead — officially turtle soup, actually opium poisoning (confirmed murder, covered up by Commissioner Utterson)
- Party arrived in Stockholm, checked into [[Golden Peace]] hotel; met contact [[Erik Johan Stagnelius]] (poet, Sverker's close friend)
- Erik names understudy [[Rufus Holberg]] as prime suspect — Sverker refused to step aside for him; Rufus has an alibi
- Interviewed Commissioner [[Gabriel Utterson]] and Coroner [[Coroner Volk|Volk]]: all victims died from violent animal-like tearing wounds; murder dates follow a pattern — another killing may be imminent
- [[Whitehill]] slums: a "disease" is actually forced limb transplants by a blonde, clean-shaven perpetrator; most victims die from rejection
- Party escorted a surviving transplant victim ([[Mutilation]]) to [[Seraphim Hospital]]; he died during treatment
- At the hospital, interviewed [[Dr. Tyko Gregorius]]: surgery is technically skilled, supplies likely diverted from a hospital; [[Dr. Svardh]] (senior physician who visits Whitehill) is a person of interest
- Party spotted the next serial murder victim: a man with his abdomen torn out, found in a church; [[Killian]]'s dark secret triggered by the wound
- Pending leads: [[Dr. Svardh]] (Sunday morning), [[Sigrid]] (National Archives), [[Professor Liebholz]] (ghost show at [[Bern's Salon]]), Whitehill surgery location, Royal Opera / Rufus Holberg, strangled young women, hospital administrator Anna (Monday)
- [[Abraham]] has a green gemstone jewelry piece left by [[Franzibald Hansen]] (Danish author, has the Sight, works with the Society) to research

### Key Recurring NPCs
- [[Linnea Elfeklint]] — last original Society member, lives at Uppsala asylum, mentor figure
- [[Algot Frisk]] — castle butler
- [[Sigrund Hierta]] — journalist, Uppsala, ally/contact
- [[Olaus Klint]] — private detective, [[Rosenberg Faction]] (believes Vaesen are evil), not an ally
- [[August T. Lysander]] — wealthy Stockholm occultist, client for current adventure
- [[Gabriel Utterson]] — Stockholm Police Commissioner, Lysander's friend; covering up Mortimer's murder; dismisses the coroner
- [[Erik Johan Stagnelius]] — poet, permanent resident at the Golden Peace, Sverker's close friend
- [[Coroner Volk]] — Stockholm city coroner; sharp and forthcoming; key forensic source
- [[Dr. Tyko Gregorius]] — junior doctor at [[Seraphim Hospital]]; provided transplant surgery intel
- [[Dr. Svardh]] — senior physician at [[Seraphim Hospital]]; visits Whitehill; **person of interest**

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
5. Tag all new/updated files with relevant location tags (`#uppsala`, `#sigtuna`, `#stockholm`, etc.) and investigation status tags (`#investigating` or `#resolved`) where applicable
6. Update the **Key Recurring NPCs** section in this file
7. Update the relevant **Adventure summary** section in this file — keep it short and concise, most important details only
