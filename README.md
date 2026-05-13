# Historical-Writing---Claude-Skill-V2
A claude wrighting skill for History, It covers the whole job. Research architecture, character construction, period voice, sensory immersion, credibility management, structural planning, and a multi-point audit protocol that runs against finished drafts.


# historical-fiction-master

**Author:** TABARC-Code
**Version:** 2.0
**Format:** Claude Skill (.skill)

---

## What This Is..

A Claude Skill. Not a chatbot prompt, not a style guide stapled to a system message — a structured, source-derived, auditable knowledge package that installs into a Claude environment and gives it the operational craft intelligence of an experienced historical fiction practitioner.

It covers the whole job. Research architecture, character construction, period voice, sensory immersion, credibility management, structural planning, and a multi-point audit protocol that runs against finished drafts. The skill navigates between ten interconnected nodes, each with its own doctrine, decision rules, and cross-references. It knows when to call a subskill. It knows when to stop and push back.

Version 2.0 is a significant expansion on the original. New nodes, new reference files, new doctrine derived from additional source material. The upgrade details are in their own section below.

---

## The Problem It Solves

Historical fiction fails in specific, diagnosable ways. The prose is right but the world is wrong. The character is vivid but thinks in vocabulary that won't exist for another three centuries. The research is deep but the novel never starts because the research is never finished. The hero is sympathetic but sanitised — scrubbed clean of the beliefs his era gave him, dressed in period costume but thinking in modern categories.

These are not vague craft failures. They are specific problems with specific causes and specific fixes.

I have ond most Most writing tools handle them the way a horoscope handles your week (its all shit...) — general enough to feel relevant, too vague to be useful. This skill does not do that. It operates from a named problem to a named doctrine to an actionable decision. If your character is anachronistic in their consciousness, the skill tells you precisely what that means, why it happens, and how to fix it. If your research has metastasised into Kudzu — more material than story — there is a protocol for that. If you have over-researched in the Flaubert way (so saturated with documented fact that you cannot let fiction breathe), there is a protocol for that too. Different problems. Different protocols.

That is the point of building a skill rather than writing a prompt.

---

## Core Philosophy (The Short Version)

*Once upon a time, it was now.*

The past must be felt, never announced. A historical novel is'nt a time-travel tour led by a narrator who keeps reminding you where and when you are. It is a state of temporal immersion so complete that the reader forgets the present entirely — including their foreknowledge of how events turn out.

This is achieved through verisimilitude, which is the governing word for everything this skill does. Not accuracy in the pedantic sense. Not historical correctness as a performance of conscientiousness. The *appearance or semblance of truth* — which is a more demanding standard, not a more relaxed one, because it requires that the world feel real from the inside as well as check out against the record from the outside.

The novelist stands in the river of time facing both directions simultaneously. The historian faces backward and points. The novelist drags the reader into the past and makes them look forward into uncertainty. That is the formal difference between the two disciplines, and it is the foundation on which this skill is built.

---

## What's New in Version 2.0

The original skill covered the core craft well. Immersion, sensory writing, research methods, character biography, period voice, structure, credibility. Solid architecture.

What it lacked was doctrine for several failure modes that the original source material didn't address systematically. Three additional source texts were ingested for this version. The gaps they revealed — and the fixes developed — are as follows.

**The Rosy Past Problem [Node H]** is new. It addresses the single most common starting condition for a historical novelist: the idealised image of the period, shaped by childhood reading, national mythology, or nostalgia. That image must be diagnosed, named, and actively corrected. Node H provides the Nostalgia Audit, the Sanitisation Prohibition, the Warts and All Imperative, and the Axe Audit. Together they form the pre-writing honesty protocol that the original skill had no mechanism for.

**Embodied Research [Node I]** is new. Screen research produces facts. Physical research produces the temperature of the prose. This node covers site visits, archive handling, re-enactor consultation, the Tool Principle (learn to use it before you write it), and the Peripheral Vision Principle — the doctrine that the most consequential research discoveries are always tangential, always found while looking for something else, and always lost when you send someone else to look. Accompanied by a full new reference file: `references/embodied-research.md`.

**Historical Cruelty and Social Control [Node J]** is new. A historical world in which characters feel no peripheral awareness of the systems of punishment and social terror that governed daily life is a falsified world. This node covers researching the teeth of authority, the period-accurate cost of defiance, and the rendering of historical perpetrators as human beings operating within systems — not cartoon villains. Moral complexity, not exculpation.

**Sentiment Archaeology** is new. A full reference file: `references/sentiment-archaeology.md`. History records events. It does not record what a person felt at three in the morning before the battle. The novelist's obligation is'nt to *invent* the inner life of the past but to *recover* it — to work backward from the fragmentary evidence that survived to reconstruct what the full interior must have been. The *petits faits vrais* doctrine, the Three Questions for any interior moment, and the Feuchtwanger metaphor principle are all here.

**The Flaubert Protocol** is new, appended to the Research Architecture node [B5]. Flaubert spent five years researching Carthage and produced a book that failed to take off into imagination because he could not let go of his documented facts. Robert Graves read everything, soaked himself in Claudius, then cast the research away and wrote the character free. Both are over-research — one is the Kudzu problem (too much material), the other is the Flaubert problem (too attached to the material). Different causes, different fixes. Both now in the skill.

**Books by Buffs** and **The Hidden Face of History** are new additions to `references/research-methods.md`. The former covers the niche specialist publishers and obsessive amateurs who have documented the physical reality of specific historical periods with a granularity no general history ever reaches. The latter covers what was never recorded at all — the products of imperceptible change and extended duration that no contemporary thought worth writing down.

**Motivated Testimony** and the **Shawano Principle** are new in `references/truth-calibration.md`. Every primary source account was written by someone who was somewhere specific, on a particular side, with particular reasons to tell the story the way they did. Understanding the witness is as important as understanding the content. The Shawano Principle: an eyewitness who has had decades to read the official history will often report the official history, not what they saw. The account closest to the event — before the consensus hardened — is frequently more authentic, even if more confused.

The **Audit Protocol** has been expanded from eight to twelve checks, with four new entries covering the rosy past, sanitisation, historical cruelty stakes, and research quality.

The **Quick-Reference Rules** have been expanded from twelve to seventeen.

The **trigger description** in the frontmatter has been substantially expanded to catch more use-cases, including the common situation where a writer doesn't know they need this skill — they just know their protagonist feels wrong, or their research won't end, or their villain is cartoonish, or their 17th-century character is too much like a 21st-century character in a doublet.

---

## Skill Structure

```
historical-fiction-master/
├── SKILL.md                          ← Core skill (10 nodes, 12-point audit, 17 rules, test suite)
├── references/
│   ├── character-biography.md        ← Full biography template, white heat, illiteracy, children, POV
│   ├── embodied-research.md          ← NEW: Sites, archives, re-enactors, tools, primary documents
│   ├── period-voice.md               ← Vocabulary, dialect, anachronism categories, social codes
│   ├── research-methods.md           ← Source types, data systems, comms speed, Books by Buffs
│   ├── sensory-writing.md            ← Five-sense deployment, yucky stuff technique, simile
│   ├── sentiment-archaeology.md      ← NEW: Recovering emotional truth from fragmentary evidence
│   └── truth-calibration.md          ← Credibility, motivated testimony, sanitisation, dual consciousness
└── subskills/
    └── period-texture-engine/
        ├── period-texture-engine.md  ← Material culture, social register, constraint embedding
        └── references/
            └── period-tools.md       ← Period object and tool reference
```

Ten nodes in the core skill:

| Node | Function |
|------|----------|
| **[A] Immersion Engine** | White Heat, sensory architecture, the Now Principle, "Good Yucky Stuff" |
| **[B] Research Architecture** | Disposition, B.S. Filter, comms speed, partisanship, over-research protocol |
| **[C] Character Architecture** | Actor Principle, white heat, body-as-archive, illiteracy, children |
| **[D] Language Craft** | Period voice, anti-anachronism, social codes, dialogue, communication tech |
| **[E] Structure and Scope** | Gist, grabbers, endings, arc, the scope decision |
| **[F] Credibility and Truth-Management** | Fact/fiction boundary, invented scenes, dialogue fabrication, Then-and-Now |
| **[G] Audit Protocol** | Twelve-point draft review — anachronism, sensory, verisimilitude, rosy past, cruelty, research quality |
| **[H] The Rosy Past Problem** | Nostalgia audit, sanitisation prohibition, warts-and-all imperative, axe audit |
| **[I] Embodied Research** | Physical imperative, peripheral vision, re-enactors, the tool principle, primary document contact |
| **[J] Historical Cruelty and Social Control** | Teeth of authority, cost of defiance, moral complexity over villainy |

---

## Navigation

The skill isn't linear. It is networked. You enter where the problem is.

- Drafting a scene → A → C → D
- Evaluating a draft → G
- Planning a novel → E → B → A
- Contemporary resonance feels thin → F5 (Then-and-Now)
- Protagonist feels too modern → H
- Research won't end → B5, then G12
- Stakes feel unreal → J
- Character's inner life feels invented rather than recovered → sentiment-archaeology.md

All paths are bilateral. Every node cross-references its neighbours. The audit protocol is the convergence point — it touches every other node and tells you where the draft has failed and where to go to fix it.

---

## Installation

Drop the `.skill` file into your Claude Skills directory. The skill will appear in your available skills list on next load. The full reference hierarchy loads progressively as needed — the core SKILL.md is always in context; reference files are called only when their specific domain is active.

Requires Claude Sonnet 4.6 or later.

---

## A Note on What This Skill isn't

It isn't a plot generator. It isn't a character name randomiser. It isn't a "write my historical novel for me" shortcut.

It is a craft system. It gives Claude the operational knowledge of an experienced practitioner — the doctrine, the decision rules, the failure modes, the corrective protocols — and applies that knowledge to whatever work is in front of it. The writer still has to write. The skill makes the writing more honest, more grounded, and more likely to survive the scrutiny of a reader who knows the period.

If you want a tool that produces historical fiction on demand without craft discipline, this isn't it. If you want a tool that makes the craft discipline tractable — that gives you the right question at the right moment, tells you which failure mode you've hit, and points you to the fix — then this is exactly it.

---

## Compatibility

| Environment | Status |
|-------------|--------|
| Claude.ai (web) | Supported |
| Claude Desktop | Supported |
| Claude API (with skills) | Supported |
| Claude Code | Supported |

---

## Licence and Attribution

© TABARC-Code. All rights reserved.

Skill doctrine is derived from source material in accordance with the Source-Bound Skill Forge methodology. Source material isn'tt named in the skill package itself — this is a deliberate bias-prevention measure, not an omission. Doctrine is expressed as operational rules, not attributed claims.

---

## Changelog

### v2.0
- Added Nodes H (Rosy Past), I (Embodied Research), J (Historical Cruelty)
- Added `references/embodied-research.md` (new)
- Added `references/sentiment-archaeology.md` (new)
- Expanded `references/truth-calibration.md`: motivated testimony, Shawano Principle, sanitisation doctrine, dual consciousness
- Expanded `references/research-methods.md`: Books by Buffs, Hidden Face of History, Peripheral Vision, internet reliability gradient
- Added B5 (Over-Research Protocol / Flaubert Problem) to Research Architecture
- Expanded Core Philosophy with Beating Heart doctrine
- Expanded Audit Protocol from G8 to G12
- Expanded Quick-Reference Rules from 12 to 17
- Expanded trigger description in frontmatter
- Added test suite
- Source identity suppression audit completed

### v1.0
- Initial release
- Nodes A–G
- References: character-biography, period-voice, research-methods, sensory-writing, truth-calibration
- Subskill: period-texture-engine

---

*TABARC-Code builds Claude Skills for practitioners who need craft intelligence, not content generation.*
---

It covers the whole job. Research architecture, character construction, period voice, sensory immersion, credibility management, structural planning, and a multi-point audit protocol that runs against finished drafts.

---
