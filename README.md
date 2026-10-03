# Lorever

**The histories of Azeroth, uncovered as you travel.**

Lorever is a free lore add-on for **World of Warcraft: Forever**. It turns Azeroth into a book that writes itself as you play: about 2,000 pages of lore and more than 330 writings, which start hidden and are revealed by what you do in the world. A narrator can read them to you while you ride.

- **Download:** [Lorever on CurseForge](https://www.curseforge.com/wow/addons/lorever)
- **Talk to us:** [Discord](https://discord.gg/vGWQVRFpt)
- **Report something:** [open an issue here](../../issues/new/choose)

This repository is the public home of the Lorever community: how the add-on works, what it holds, and where players send reports.

---

## Voice packs: download and install

Every language has two voices: every lore page, already narrated by a natural storyteller (about 30 hours). Pick the one you like, or install both.

| Language | Voice | Download |
| --- | --- | --- |
| English | Michael | [LoreverNarration_enUS-0.1.0.zip (564 MB)](https://github.com/acappa221b/Lorever-Community/releases/download/Lorever-Narration-English-Michael/LoreverNarration_enUS-0.1.0.zip) |
| English | Heart | [LoreverNarration_enUS_F-0.1.0.zip (537 MB)](https://github.com/acappa221b/Lorever-Community/releases/download/Lorever-Narration-English-Heart/LoreverNarration_enUS_F-0.1.0.zip) |
| Português (Brasil) | Santa | [LoreverNarration_ptBR-0.1.0.zip (566 MB)](https://github.com/acappa221b/Lorever-Community/releases/download/Lorever-Narration-Portugues-do-Brasil-Santa/LoreverNarration_ptBR-0.1.0.zip) |
| Português (Brasil) | Dora | [LoreverNarration_ptBR_F-0.1.0.zip (538 MB)](https://github.com/acappa221b/Lorever-Community/releases/download/Lorever-Narration-Portugues-do-Brasil-Dora/LoreverNarration_ptBR_F-0.1.0.zip) |
| Deutsch | Thorsten | [LoreverNarration_deDE-0.1.0.zip (550 MB)](https://github.com/acappa221b/Lorever-Community/releases/download/Lorever-Narration-Deutsch-Thorsten/LoreverNarration_deDE-0.1.0.zip) |
| Deutsch | Kerstin | [LoreverNarration_deDE_F-0.1.0.zip (523 MB)](https://github.com/acappa221b/Lorever-Community/releases/download/Lorever-Narration-Deutsch-Kerstin/LoreverNarration_deDE_F-0.1.0.zip) |
| Français | Gilles | [LoreverNarration_frFR-0.1.0.zip (557 MB)](https://github.com/acappa221b/Lorever-Community/releases/download/Lorever-Narration-Francais-Gilles/LoreverNarration_frFR-0.1.0.zip) |
| Français | Siwis | [LoreverNarration_frFR_F-0.1.0.zip (559 MB)](https://github.com/acappa221b/Lorever-Community/releases/download/Lorever-Narration-Francais-Siwis/LoreverNarration_frFR_F-0.1.0.zip) |
| Español | Santa | [LoreverNarration_esES-0.1.0.zip (588 MB)](https://github.com/acappa221b/Lorever-Community/releases/download/Lorever-Narration-Espanol-Santa/LoreverNarration_esES-0.1.0.zip) |
| Español | Dora | [LoreverNarration_esES_F-0.1.0.zip (558 MB)](https://github.com/acappa221b/Lorever-Community/releases/download/Lorever-Narration-Espanol-Dora/LoreverNarration_esES_F-0.1.0.zip) |
| 简体中文 | Yunxi | [LoreverNarration_zhCN-0.1.0.zip (469 MB)](https://github.com/acappa221b/Lorever-Community/releases/download/Lorever-Narration-Chinese-Yunxi/LoreverNarration_zhCN-0.1.0.zip) |
| 简体中文 | Xiaoxiao | [LoreverNarration_zhCN_F-0.1.0.zip (515 MB)](https://github.com/acappa221b/Lorever-Community/releases/download/Lorever-Narration-Chinese-Xiaoxiao/LoreverNarration_zhCN_F-0.1.0.zip) |
| Русский | Dmitri | [LoreverNarration_ruRU-0.1.0.zip (507 MB)](https://github.com/acappa221b/Lorever-Community/releases/download/Lorever-Narration-Russian-Dmitri/LoreverNarration_ruRU-0.1.0.zip) |
| Русский | Natasha | [LoreverNarration_ruRU_F-0.1.0.zip (519 MB)](https://github.com/acappa221b/Lorever-Community/releases/download/Lorever-Narration-Russian-Natasha/LoreverNarration_ruRU_F-0.1.0.zip) |

1. Install **Lorever** (version 1.8.0 or newer) from [CurseForge](https://www.curseforge.com/wow/addons/lorever).
2. Download a zip from the table.
3. Open the zip. Inside there is one folder, for example `LoreverNarration_enUS`.
4. Put that folder in your game's add-ons folder: `World of Warcraft\Interface\AddOns`, next to `Interface\AddOns\Lorever`.
5. Start the game, or type `/reload` if it is already running.
6. Open any Lorever page and press **Listen**.

Good to know:

- A pack is used when Lorever shows its content in that pack's language, with the voice on **Automatic** or **Voice pack** in `/lorever narrator`.
- With two voices for one language, choose one under **Pack** in `/lorever narrator`.
- If a line has no recording, your other pack or the game's own voice reads that line. Nothing breaks.
- A pack is only sound files and a small index. No program runs outside the game.

More about the packs, CurseForge and recording your own voice: [Voice packs](#voice-packs).

---

## Contents

- [Voice packs: download and install](#voice-packs-download-and-install)
- [How it works, from start to finish](#how-it-works-from-start-to-finish)
- [What Lorever has today](#what-lorever-has-today)
- [The book of lore](#the-book-of-lore)
- [Literature](#literature)
- [Finding what is left](#finding-what-is-left)
- [The narrator](#the-narrator)
- [Voice packs](#voice-packs)
- [Languages](#languages)
- [Commands](#commands)
- [Options](#options)
- [Move things where you like](#move-things-where-you-like)
- [Works with other add-ons](#works-with-other-add-ons)
- [Safe and private](#safe-and-private)
- [Questions](#questions)
- [Report something](#report-something)
- [AI disclaimer](#ai-disclaimer)

---

## How it works, from start to finish

1. **Install it.** Get Lorever from CurseForge. There is nothing to set up.
2. **Open the book.** A Lore tab sits beside the quest log; `/lorever` and the minimap button open it too. At first almost every page is locked, hidden in the fog.
3. **Play as you always do.** Pages unlock by themselves:

   | You do this | Lorever reveals |
   | --- | --- |
   | Walk into a zone, city or subzone | The page of that land or place |
   | Speak with a figure, or pass the mouse over them | The page of that figure |
   | Target a hostile figure | The page of that figure |
   | Turn in a quest | A chapter of a figure's story, or a page the quest tells of |
   | Defeat a dungeon or raid boss | The page of that boss |
   | Open a book, letter or plaque in the world | That writing, in your library |
   | Click a link inside a page you know | The page it leads to |

4. **Watch your knowledge grow.** A banner tells you what you found. Each discovery gives experience to one of two bars: **Lore** or **Literature**. Neither level has a cap.
5. **Read, or listen.** Every name in a page is a link to its own page. Press **Listen** and the narrator reads the page aloud while you keep playing.
6. **Go after what is left.** Turquoise marks show the figures and writings you have not found yet: above their heads, on the world map and on the minimap. The Lore tracker lists the nearest ones.

---

## What Lorever has today

| | |
| --- | --- |
| **Pages of lore** | About 2,000: zones, cities, dungeons, raids, places, figures, peoples, orders and events |
| **Writings** | 330+ books, letters, journals, legends and inscriptions, each with where to find it |
| **Progressions** | A **Lore** level and a **Literature** level, each with its own experience bar and no cap |
| **Narrator** | Reads any page aloud, with a queue, a small control bar and a travel mode for flights |
| **Voice packs** | Optional add-ons with every page already narrated by a storyteller: English, Português, Deutsch, Français, Español, 简体中文, Русский |
| **Languages** | English, Português (Brasil), Deutsch, Français, Español (Spain and Latin America), 简体中文, Русский |
| **Looks** | Three looks for the book: Lorever (parchment), Dark, and Classic (the game's quest window) |
| **Price** | Free. No donations asked in game, no ads |

---

## The book of lore

- **Here:** the zone you stand in, how much of it is still in the fog, and what is left to find.
- **Regions, Categories, A–Z:** every page, with search.
- **A region page** tells its history, then lists its places, its figures of note and the other pages that belong to it.
- **A figure page** has a summary, the figure's significance and deeds, **chapters** that unlock one by one, **mentions**, and **bonds**: the web of relations to other figures.
- **Links** have three colors: ink blue for a page you know, faded blue for a page not yet discovered, faded red for a page not yet written. Hover for a preview, click to open.

### Experience

| Discovery | Experience |
| --- | --- |
| Zone, city, dungeon | 40 Lore |
| Raid | 60 Lore |
| Place (subzone) | 10 Lore |
| Figure (major / notable / minor) | 50 / 30 / 15 Lore |
| Chapter of a figure | 25 / 15 / 10 Lore |
| People, faction, event | 25 Lore |
| Other topic | 20 Lore |
| Mention | 5 Lore |
| Book or legend / journal / letter / inscription | 25 / 20 / 15 / 10 Literature |

Level 1 to 2 needs 100 experience, and each level asks a little more than the one before. There is no last level: when new lore is written, there is simply more to earn.

---

## Literature

A catalogue of every book, letter, journal, legend and inscription in the world, in the manner of a collection log.

- **By Region**, **Missing** (with where to find each one), **Read** and **Unlisted** (writings you read that the catalogue did not know yet).
- Filter by kind: Books, Letters and Notes, Journals, Legends, Inscriptions. Search by title.
- **Lorever ships no book text.** When you read a writing in the world, the pages you see are kept on your own computer, and the writing's page in Lorever shows them from then on.
- **A note beside an open book** says how many of its pages are kept ("3 of 6 pages kept"). Lorever never turns a page for you: turn them yourself to keep the whole text.
- **A writing in your bags is found** as soon as you pick it up, before you open it.
- A writing with copies in several lands is listed in each of them, and its page says where you read it.
- Item tooltips say whether you have read a book, letter or journal.

---

## Finding what is left

| | |
| --- | --- |
| **Turquoise "!"** | Above undiscovered figures (needs friendly NPC nameplates: `/lorever nameplates`) and on the world map |
| **Book icon on the map** | Each place where a writing you have not read can be found |
| **Minimap** | The nearest undiscovered figures and writings; what you track stays on the edge, pointing the way |
| **Continent maps** | Each zone shows how many figures and writings are left there |
| **Lore tracker** | A short list under the quest tracker: what you track, plus the nearest undiscovered lore of the zone, with distances |
| **Track and waypoint** | Every page with a place has **Track** and **Set waypoint** |
| **Lore button on your target** | When your target is a figure with a page, a small book button appears by the target frame. Click it to read |
| **Right-click a figure** | A right-click on a friendly figure that opens no window of its own opens its lore page. Never in combat |
| **Tooltips** | "Lore: undiscovered", or the figure's page and how much of it you know |
| **Quest windows** | A quest that reveals lore says so beside its window |

---

## The narrator

Press **Listen** on any page. A small bar stays on screen with **pause**, **next section**, **back** and **stop**, so you can close the book and keep playing.

- A **queue** ("Listen next"). It remembers where it stopped, even after `/reload`.
- **Travel mode:** on a flight, it reads the lands you fly over.
- It can **pause in combat** and read each new discovery aloud.
- It reads only what you have discovered.

In the **narrator panel** (`/lorever narrator`) you choose who reads each kind of page, in each language:

| Kind of page | Default style |
| --- | --- |
| Regions and places | **Chronicler**: calm and clear, like an encyclopedia |
| Figures | **Chronicler** |
| Peoples, orders and events | **Epic**: deep and slow, for great events |
| Books and legends | **Storyteller**: warm and unhurried |
| Letters and journals | **Serene**: light and gentle |

Copy a style to make your own profile, with voice, speed and volume. Every row has a **Test** button. At the top of the panel you choose the voice: **Automatic**, the game's **built-in text to speech**, or a **voice pack**.

---

## Voice packs

By default the narrator uses the game's own text to speech. If that sounds too robotic, install the **Lorever Narration** pack of your language: every page and every book, already narrated by a calm, natural storyteller. About 30 hours in each language.

| Language | Voice pack |
| --- | --- |
| English | [Lorever Narration (English)](https://www.curseforge.com/wow/addons/lorever-narration-english) |
| Português (Brasil) | [Lorever Narration (Português do Brasil)](https://www.curseforge.com/wow/addons/lorever-narration-portugues-do-brasil) |
| Deutsch | [Lorever Narration (Deutsch)](https://www.curseforge.com/wow/addons/lorever-narration-deutsch) |
| Français | [Lorever Narration (Français)](https://www.curseforge.com/wow/addons/lorever-narration-francais) |
| Español (Spain and Latin America) | [Lorever Narration (Español)](https://www.curseforge.com/wow/addons/lorever-narration-espanol) |
| 简体中文 | [Lorever Narration (简体中文)](https://www.curseforge.com/wow/addons/lorever-narration-chinese) |
| Русский | [Lorever Narration (Русский)](https://www.curseforge.com/wow/addons/lorever-narration-russian) |

- **Nothing to set up.** Install the pack beside Lorever. With the voice on Automatic, the narrator uses it by itself.
- **Only an add-on.** Sound files and a small index. No program runs outside the game.
- **Never silent.** A line without a recording (new text after an update) is read by the game's own voice.
- **Two voices per language.** The packs on CurseForge use the first voice. Both voices of every language are in the table at the [top of this page](#voice-packs-download-and-install). Choose between your packs under **Pack** in `/lorever narrator`.
- **Your own voice.** With [Lorever Voice Studio](https://github.com/acappa221b/Lorever-Voice/releases/latest), a free Windows app, you read the lore aloud and export a pack of your own (English, the lands of levels 1 to 20 for now).

---

## Languages

| Language | Interface | Lore | Literature | Voice pack |
| --- | --- | --- | --- | --- |
| English | ✔ | ✔ | ✔ | ✔ |
| Português (Brasil) | ✔ | ✔ | ✔ | ✔ |
| Deutsch | ✔ | ✔ | ✔ | ✔ |
| Français | ✔ | ✔ | ✔ | ✔ |
| Español (España y Latinoamérica) | ✔ | ✔ | ✔ | ✔ |
| 简体中文 | ✔ | ✔ | ✔ | ✔ |
| Русский | ✔ | ✔ | ✔ | ✔ |

Names of places, factions, races, classes and books are the **official names of each language's game client**. Lorever follows your game's language; `/lorever language` changes it. On any other client language, Lorever works in English.

When you meet a figure or open a book, the name your game shows becomes the name on its page.

---

## Commands

| Command | What it does |
| --- | --- |
| `/lorever` | Opens the book of lore |
| `/lorever level` | Your Lore and Literature levels |
| `/lorever options` | Opens the options |
| `/lorever nameplates` | Turns on friendly NPC nameplates, so the turquoise marks can appear |
| `/lorever listen` | The narrator reads the land you stand in |
| `/lorever pause` | Pauses or resumes the narrator |
| `/lorever stop` | Stops the narrator and clears its queue |
| `/lorever narrator` | The narrator panel: voices, styles and speed for each kind of page |
| `/lorever voices` | Lists the game's voices installed on your computer |
| `/lorever voice <number>` | Picks the game voice the narrator uses (`/lorever voice auto` goes back to the automatic choice) |
| `/lorever voicetest` | The narrator says one sentence and tells which voice it uses |
| `/lorever language auto\|en\|pt\|de\|fr\|es\|zh\|ru` | The add-on's language (`auto` follows the game). Then `/reload` |
| `/lorever theme lorever\|dark\|classic` | The look of the book |
| `/lorever banner` | Shows a sample banner, to drag the banners where you want them |
| `/lorever resetpos` | Puts the lore window, the banners and the buttons back in their places |
| `/lorever found` | Where you found writings whose place the catalogue did not know |
| `/lorever export` | Your community reports, as text to paste in an issue here |
| `/lorever where` | The current map, zone, subzone and position (useful in a lore correction) |

Key bindings are under **Options > Keybindings > AddOns > Lorever**: open the book, narrator play or pause, read this land. The minimap button opens the book with a click and the narrator with a right-click.

---

## Options

**Esc > Options > AddOns > Lorever.** Every part of Lorever can be turned off on its own.

| Group | Options |
| --- | --- |
| **Progress** | Share lore across your characters, or let each character discover the world alone |
| **Finding lore** | Marks above figures · marks on the world map · marks on the minimap · unread books on the map · lore left on continent maps · also mark discovered figures · discover figures at a glance (mouse over) |
| **Tracker** | Lore tracker · track the nearest lore |
| **Narrator** | Read lore aloud · narrator bar · pause in combat · read discoveries aloud · travel mode |
| **Look** | Look of the book: Lorever, Dark or Classic |
| **Windows and tooltips** | Lore tab in the quest log · minimap button · book button on the world map · lore button on your target · right-click a figure to open its lore · lore in quest windows · lore line on tooltips · Literature on item tooltips |
| **Books** | Pages kept, beside an open book · find writings by picking them up |
| **Banners** | Discovery banners · discovery sounds |
| **Questie** | Use Questie icons |

---

## Move things where you like

Hold **Shift** and drag to move the discovery banners, the Lore tab by the quest log, the book buttons on the map and the lore button on your target. The lore window moves by dragging its top, and opens again where you left it. `/lorever resetpos` puts everything back.

---

## Works with other add-ons

- **Questie:** fully compatible. The Lore tracker sits right under Questie's, and with **Use Questie icons** Lorever's marks are drawn by Questie and follow its show and hide buttons.
- **TomTom:** waypoints use TomTom's arrow when it is installed, else the game's own.

---

## Safe and private

- Lorever **never** sends chat messages, never automates anything, and stays out of Blizzard's menus and panels.
- No program runs outside the game.
- No account and no tracking. Nothing about you or your characters leaves your computer.
- Lorever ships **no Blizzard text, art or audio**. Book text is read from your own game and stays on your computer.

---

## Questions

**Does it work with Questie?** Yes. Lorever is built to sit beside it.

**Do I need a voice pack?** No. Without one, the narrator uses the game's own voice.

**Why can't I see the "!" above figures?** Turn on friendly NPC nameplates: `/lorever nameplates`. Inside dungeons the marks are not shown.

**The narrator says nothing.** Turn on Text to Speech in the game's options (Accessibility) and pick a voice there, then try `/lorever voicetest`.

**I changed the language and nothing happened.** Type `/reload`.

**Does my progress carry between characters?** Yes, by default. The option **Share lore across characters** turns that off.

**Is my language missing?** Tell us on Discord or in an issue. More languages are on the way.

---

## Report something

Open **[Issues > New issue](../../issues/new/choose)** and pick a form:

- **Literature report:** writings found in places the catalogue does not know yet. In game, type `/lorever export`, press Ctrl+C, and paste the text into the form.
- **Lore correction:** a mistake in a page of lore, a wrong name in a translation, or a figure or place that is missing.
- **Bug report:** something in Lorever does not work.

### What a Literature report holds

Only the title of each writing, its map position, how many times it was seen, dates, the add-on version and the game language. No character, guild, account or realm names. Nothing is sent by the add-on on its own: you choose what to paste here.

---

## AI disclaimer

- **The lore.** All of Lorever's lore was written with the help of AI. The AI worked only from facts found in the game itself and in Blizzard's official sources, and was told never to invent events, family ties or "lost chapters". The text is our own: no book, quest or dialogue text from the game is copied into the add-on. The translations were also made with AI, using each game client's official names for places, factions, races, classes and books. If you spot a mistake, please tell us and we will fix it.
- **The game's own voice.** By default, Lorever reads with World of Warcraft's built-in text to speech. No AI is involved.
- **The voice packs (optional).** The narration in the Lorever Narration packs was generated with AI text-to-speech models, on the author's own computer: Kokoro-82M (Apache-2.0) for English, Português, Español, 简体中文 and the Siwis voice in Français, Kokoro German Kerstin by kikiri-tts (Apache-2.0) for the Kerstin voice in Deutsch, and Piper voices (CC0) for the Thorsten voice in Deutsch, the Gilles voice in Français and the Dmitri voice in Русский, and Vosk TTS by Alpha Cephei (Apache-2.0) for the Natasha voice in Русский. Packs that players record with Lorever Voice Studio hold their own voice. Only Lorever's own text is read. The packs hold no audio, text or art from Blizzard, and no text from the game's books. No online AI service was used, and no real person's voice was cloned or imitated.

---

## Notice

Lorever is an unofficial, free fan-made add-on and is not made, endorsed, sponsored or approved by Blizzard Entertainment, Inc. World of Warcraft® and Warcraft® are trademarks or registered trademarks of Blizzard Entertainment, Inc., in the U.S. and/or other countries. All World of Warcraft content, names, places, characters, book titles and in-game assets referenced by this add-on are the property of Blizzard Entertainment, Inc. Lorever ships no Blizzard art, audio or book text; book text is read from your own game client and stored only on your computer.

Lorever © 2026 acappa221b. All rights reserved.
