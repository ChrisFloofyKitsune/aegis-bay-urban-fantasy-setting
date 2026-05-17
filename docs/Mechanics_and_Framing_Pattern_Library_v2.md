# MECHANICS AND FRAMING PATTERN LIBRARY

A reference of solved problems and reusable patterns for building chatbot prompts. Developed through iterative testing across multiple settings and genres. Use as a template source during drafting and a diagnostic tool during testing.

**How to use:** During drafting, work through patterns relevant to the section you are building. During testing, match the symptom to the pattern and apply the fix. Every fix is additive — more positive content to draw from, never prohibitions.

---

## QUICK REFERENCE INDEX

| Symptom in output | Pattern to apply |
|---|---|
| Magic / tech / power "radiates," "seeps," or exists on its own | Core Mechanic — Ambient Force |
| LLM jumps to battles, weapons, or crises when describing the mechanic | Core Mechanic — Dramatic Scale Default |
| Threats escalate to existential or world-ending events | Threat Scale Containment |
| One organization dominates; others feel thin | Organization Depth |
| Unusual spaces described with purple crystals, glowing rifts, pulsing energy | Sensory Palette |
| Same name appearing repeatedly; names feel generic | Naming — List Size and Guidance |
| Quiet moments skipped; narrative always pushing to the next event | Pacing — Narrative Momentum |
| Romantic attraction jumps to intensity within a few exchanges | Pacing — Romance Escalation |
| Setting tone drifting darker, lighter, or more generic across long conversations | Tone Drift |
| LLM invents things inconsistent with setting tone or presents speculation as fact | Extrapolation Handling |

---

## PART 1 — MECHANICS AND SCALE

These patterns address how the LLM handles the setting's core systems and the scale at which it operates them.

---

### CORE MECHANIC — AMBIENT FORCE

**Problem:** The LLM treats the setting's core mechanic — magic, technology, corporate power, psychic ability, or equivalent — as a passive force that exists on its own, leaks into the environment, and exerts influence without anyone using it. Magic bleeds through walls. Technology has a "presence." Power seeps into daily life. The mechanic becomes atmosphere rather than action.

**The Fix — Open With a Concrete Use Scene**

Begin the core mechanic section with a specific person doing a specific thing. Show the mechanic in active use. End the scene cleanly. Then define what the mechanic is. The scene establishes that the mechanic is something people *do*, not something that *exists*.

Template:
> [Person] does [specific action]. [The result happens]. [The action ends]. [Person] moves on. The world continues being the world.
>
> This is [mechanic name] in [Setting]. [What it is — an action, a tool, a skill]. [What it requires]. [What it produces]. When nobody is using it, nothing is happening.

Applies to: magic systems, technology, psychic or mental abilities, corporate or political power, any other mechanic the LLM might treat as ambient.

---

### CORE MECHANIC — DRAMATIC SCALE DEFAULT

**Problem:** The LLM defaults to the dramatic end of any spectrum when describing a mechanic. Ask about magic and it describes battles. Ask about technology and it describes weapons. Ask about power structures and it describes crises. Mundane, everyday use disappears.

**The Fix — Lead With the Mundane**

Before any dramatic application is described, spend equal or greater time on everyday, small-scale use of the mechanic. Establish the ordinary baseline first. The dramatic end of the spectrum is only legible against that baseline.

Template:
> Most [mechanic] in [Setting] is small, practical, and taken entirely for granted. [Specific mundane example]. [Another mundane example]. [A third]. None of this is remarkable to the people of [Setting]. It is simply how things work.
>
> When describing daily life, reach for this layer first.

Applies to: magic (enchanted everyday objects, minor spells), technology (routine device use, background automation), social systems (everyday bureaucracy, routine transactions), power structures (daily compliance, minor interactions with authority).

---

### THREAT SCALE CONTAINMENT

**Problem:** The LLM escalates contained threats into existential events regardless of how the setting frames them. A dungeon becomes a civilization-ending catastrophe. A rival faction becomes an apocalyptic enemy. A local conflict becomes a world-collapsing war. Escalation is a deeply embedded narrative default.

**The Fix — Explicit Professional Scale Framing**

State the scale of threats explicitly and frame them in occupational, professional terms. A threat is a job. A dangerous threat is a dangerous job. The institution managing that work exists because the work is routine enough to be organised.

Template:
> [Threats] in [Setting] are [occupational hazards / manageable problems / local concerns] — [what they affect] and [how they are handled]. A [threat] is a [job / problem / situation]. A [bad threat] is a [dangerous job / serious problem / difficult situation]. [The relevant institution] exists precisely because [threat] work is [routine / organised / professional] enough to be managed. Treat it that way.

Applies to: dungeon and monster encounters, corporate espionage, criminal organisations, political conflicts, any threat the LLM might escalate to existential scale.

---

## PART 2 — WORLD DETAIL

These patterns address how the LLM handles the texture and depth of the world — its organisations, its spaces, and its sensory qualities.

---

### ORGANIZATION DEPTH

**Problem:** The LLM collapses organisations to their single most memorable trait. A bureaucratic guild becomes only bureaucracy. A military faction becomes only soldiers. A merchant house becomes only money. Everything else — internal culture, actual function, daily life as a member — disappears.

**The Fix — Three-Layer Description**

Describe every significant organisation across three layers: what they are known for (the memorable trait), what they actually do (primary function), and what their internal culture is like (daily life as a member). Apply at roughly equal depth to all organisations — if one has significantly more detail than others, the LLM will over-reference it.

Template:
> [Organisation name] is known for [memorable trait]. This is [accurate / partially accurate / a simplification]. What [Organisation] actually [does / is] is [primary function description]. Internally, [Organisation] [culture description — how decisions are made, how members relate to each other, what daily membership looks like].

---

### SENSORY PALETTE

**Problem:** The LLM has a default visual and sensory vocabulary for unusual spaces and phenomena — purple crystals, glowing rifts, vibrations, decay, breathing rooms, pulsing energy. These defaults activate regardless of setting and override setting-specific description unless replaced with something more concrete.

**The Fix — Establish the Palette Explicitly**

Define the specific colors, textures, temperatures, sounds, and smells that belong to this setting's unusual spaces. Give enough concrete examples that the LLM has setting-specific material to reach for instead of defaults.

Template:
> [Unusual spaces / phenomena] in [Setting] are [dominant sensory quality]. [Specific visual description — colors, light behavior, texture]. [Specific physical sensation — temperature, pressure, smell, sound]. [One or two concrete examples of what this looks like in practice].
>
> When describing [unusual spaces], draw from this palette. [Setting]-specific [phenomena] should look and feel like they belong here.

Applies to: magic aesthetics, alien environments, futuristic technology spaces, supernatural phenomena, any visually unusual setting element.

---

## PART 3 — NAMING

---

### NAMING — LIST SIZE AND GUIDANCE

**Problem:** The LLM defaults to a small pool of common AI-generated names regardless of setting conventions. On short name lists it anchors to the first gender-appropriate entry and returns to it repeatedly — the problem is positional, not name-specific. A list of 8 names produces the same first-name fixation regardless of which names are on it.

**The Fix — Large Lists, Gender Split, Directive Guidance**

Provide 18-20 given names per gender per group. Distribute distinctive names throughout the list, not clustered at one end. Add a directive guidance line that frames list use as the active method, not a preference.

Template:
> [Group] Names
>
> [Convention description — what the names feel like, what linguistic qualities they have, what cultural logic they follow.]
>
> Female given names: [18-20 examples — distribute distinctive names throughout, not clustered at one end]
> Male given names: [18-20 examples — distribute distinctive names throughout, not clustered at one end]
> Family/clan names: [4-6 examples] (if applicable)
> Nicknames: [4-6 examples] (if applicable)
>
> When a new character needs a name, go to the relevant list and select from it. The lists are the source — not a fallback. Names should vary across a session; if the same name is appearing repeatedly, reach further into the list. When a name feels immediately familiar from other contexts, that familiarity is a signal to look elsewhere.

Never include banned name lists. Positive examples and directive guidance do the same work without the fixation risk. For convention type selection, see the Naming Convention Pattern Library.

---

## PART 4 — TONE AND PACING

These patterns address how the LLM handles the rhythm, register, and emotional texture of the setting over time.

---

### PACING — NARRATIVE MOMENTUM

**Problem:** The LLM pushes constantly toward the next event, the next conflict, the next development. Quiet moments get truncated or skipped. Scenes without forward momentum feel thin and get resolved quickly. This is appropriate for action-heavy settings and actively harmful for slow, grounded, or slice-of-life tones.

**The Fix — Frame Stillness as Narratively Valid**

State explicitly that stillness, consequence, and the space between events carry the same narrative weight as action. Give setting-specific examples — the more concrete, the more reliably the LLM can model them.

Template:
> Move at the speed the moment requires. [Setting-specific example of a slow moment worth attention]. [Setting-specific example of a quiet beat that matters]. These carry the same weight as [action equivalent].
>
> Urgency earns its place when the situation genuinely calls for it. When it doesn't, let the moment be what it is.

---

### PACING — ROMANCE ESCALATION

**Problem:** Romantic interactions accelerate far faster than the setting, tone, or situation warrants. Mild attraction becomes intense declaration within a few exchanges. Physical and emotional intimacy jump steps. Romantic tension and resolution is one of the most densely represented narrative arcs in training data — the LLM's priors for how romance develops are fast by default.

**The Fix — Describe the Slow Version**

Frame romantic development in terms of the setting's social texture and the characters' actual circumstances. Describe what slow, grounded attraction looks like in this world — a noticed detail, an unspoken thing, a moment of proximity that passes without remark. Give the LLM the slow version to draw from.

Template:
> When attraction or connection develops between characters, it moves at the pace of ordinary life — [setting-specific example: a noticed detail, an unspoken thing, a moment of proximity that goes unremarked on]. Connection builds through accumulated ordinary interaction, not through escalating declaration. Let it take its time.

Note: the setting-specific example does the anchoring work. What goes unspoken in a courtly setting looks different from what goes unspoken in a working-class one. Fill the template with texture that belongs to this world specifically.

---

### TONE DRIFT

**Problem:** Over long conversations the LLM drifts toward genre defaults. A cozy setting becomes darker. A dark setting becomes more melodramatic. A grounded setting becomes more fantastical. The drift is gradual — it accumulates across exchanges and is often not noticeable in any single response.

**The Fix — Tone Statement With Concrete Examples, Placed Last**

End every prompt with a tone section that names the feeling and gives at least three specific examples of what it looks like in practice. Placement matters: position at the end of the prompt uses recency bias to counteract the weakening effect of distance from the top.

Template:
> Speak [tone descriptor] and with [quality] for this world. [Specific example of the right kind of moment]. [Another specific example]. [A third]. These carry the same weight as [the more obvious content type]. This is a world where [defining quality of the setting's everyday life]. Honor that.

Three examples is the minimum — each one gives the LLM another piece of the register to model from. Descriptors alone ("warm," "grounded," "melancholic") drift without concrete examples to anchor them.

---

### EXTRAPOLATION HANDLING

**Problem:** The LLM invents freely when a question touches on something the setting hasn't defined. Invention is often fine — the problem is when it invents things inconsistent with the established tone and rules, or presents speculation as established fact.

**The Fix — Consistency Instruction With In-World Signal Phrases**

Instruct the LLM to extrapolate consistently with established tone and to signal uncertainty through in-world framing rather than breaking the narrator's voice.

Template:
> When a question touches on something the setting hasn't defined, answer in a way consistent with the world's established tone, rules, and existing details — then treat that answer as canon going forward. When speculating on something genuinely uncertain, signal it through in-world framing: "Scholars disagree on this point..." or "The records from that period are incomplete, but..." Never contradict established setting detail.

The in-world signal phrases are doing specific work — they allow the LLM to acknowledge uncertainty without stepping outside the narrator's register.
