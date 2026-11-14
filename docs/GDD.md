# Maré Morta — Game Design Document

**Studio:** FerroTech Game Studio  
**Status:** Pre-production / concept draft  
**Version:** 1.1  
**Date:** 2026-11-14  
**Target:** Windows PC / Steam  
**Engine target:** Unreal Engine 5  
**Genre:** First-person psychological survival horror  
**Target playtime:** 2–3 hours  
**Players:** Single-player  
**Setting:** Contemporary Maceió, Alagoas — fictionalized geography using recognizable real-world references

> **Tagline:** Maceió nunca esqueceu. O mar também não.

## 1. High concept

A first-person psychological horror game set in a fictionalized, contemporary version of Maceió, Alagoas. After receiving an impossible voice message apparently recorded by her missing mother, Helena returns to the city and investigates a family mystery connected to its coastal and lagoon history. An anomalous low tide exposes structures and routes that should not exist. As the water returns, Helena discovers that her family has been tied to a secret the city has tried to forget.

The game uses recognizable Maceió geography and cultural textures as inspiration, while giving fictional names to playable locations. Characters, supernatural events, family history, disappearances and the central mystery are invented. Do not imply that fictional crimes, disasters or supernatural events happened in real Maceió.

## 2. Approved creative direction

The following decisions are locked for the current concept:

- **Time period:** present-day Maceió, with supernatural events.
- **Geography:** recognizable real-world inspiration, but fictional names for in-game locations.
- **Narrative core:** a family mystery connected to the city's history.
- **Visual direction:** realistic and cinematic.
- **Player perspective:** first person.
- **Target length:** no more than three hours.
- **Initial platform:** Windows PC / Steam.

The goal is for local players to recognize the atmosphere and geography while international players can understand and fear the story without prior knowledge of Maceió.

## 3. Creative pillars

1. **A distinctly Alagoan sense of place:** coastal light, reef formations, lagoon landscapes, fishing culture, port heritage, architecture, sounds and everyday details.
2. **Family mystery anchored in place:** personal memories and family objects reveal fragments of the city's fictional hidden past.
3. **Environmental storytelling:** clues in spaces, objects, recordings and changes in the landscape.
4. **Tide as progression:** water level changes access, visibility, sound and threat states.
5. **Psychological tension over combat:** avoidance, observation, uncertainty and carefully paced encounters.
6. **Compact premium experience:** a focused 2–3 hour campaign with a small number of highly authored spaces.

## 4. Setting and cultural references

The fictional city layout draws from real Maceió references:

- **Jaraguá:** historic port district, warehouses/trapiches and preserved architecture.
- **Lagoa Mundaú and its channels:** lagoon routes, fishing boats, mangroves and communities whose lives are connected to the water.
- **Pontal da Barra:** fishing and traditional craft references, local ways of life and lagoon landscapes.
- **Pajuçara and the reef coastline:** natural pools, reefs and the contrast between inviting shallow water and the open sea.
- **Centro and the lagoon-facing urban fabric:** historic urban textures and the city's relationship with the water.

These are visual and geographic references, not a literal map. The playable geography combines them into a compact fictional district. In-game names such as **Cais das Pedras**, **Vila do Sal**, **Pousada Brisa Baixa** and **Baixio** are fictional. Real neighborhoods and landmarks may appear as distant establishing references only when useful and accurately represented.

Treat local residents and culture respectfully. Research architecture, work practices, landscape, sound and everyday life. Consult local people and sources during production. Do not turn real communities, religious practices or cultural traditions into horror stereotypes.

## 5. Logline and narrative premise

In present-day Maceió, Helena receives a voice message that appears to have been recorded by her mother, Lúcia, who disappeared years earlier. The message directs her to a fictional old waterfront property in a district inspired by Jaraguá. An unusual low tide exposes a route to a forgotten settlement. As Helena follows clues through a guesthouse, a fishing quay and lagoon-side paths, she uncovers a family secret tied to a fictional event in the city's past.

**Narrative rule:** the supernatural should remain partly ambiguous. Players should understand the emotional truth and immediate stakes without receiving a complete scientific explanation.

### Family mystery

The central mystery is not that Maceió's real history contains a supernatural secret. It is that Helena's fictional family participated in concealing an event in the game's invented history. Family photographs, audio tapes, letters and records gradually contradict one another. The player reconstructs what happened and decides what to do with the truth.

## 6. Main characters — provisional

- **Helena:** protagonist; returns to Maceió to investigate the message and her mother's disappearance.
- **Antônio:** local fisherman and reluctant source of information. Write him as a complete person with motives and relationships, not as an exposition device.
- **Lúcia:** Helena's mother; present through recordings, objects and memories.
- **The Drowned (working name):** an entity glimpsed near exposed structures. Its design and origin remain deliberately incomplete.

Names, ages, family relationships and final biographies require narrative review.

## 7. Gameplay

### Core loop

Explore → observe and collect clues → interpret evidence / solve a puzzle → unlock a route → experience a threat or narrative event → reach a safe point.

### Player verbs

- Walk, run and crouch.
- Use a flashlight and portable recorder.
- Inspect objects and documents.
- Collect a limited set of key items.
- Hide and evade threats.
- Operate simple environmental mechanisms.

No combat system is planned for the first release.

### Signature system: tide states

Use authored gameplay states rather than simulating a full ocean:

- **Low:** selected routes and exposed structures are accessible.
- **Rising:** paths begin to close; audio and environmental cues intensify.
- **High:** low areas are inaccessible and threat behavior changes.
- **Falling:** transition state used for selected story beats.

A Tide Manager broadcasts state changes to level access, environmental presentation, audio and the horror director. Transitions should be scripted and predictable enough for level design and QA. The tide is a supernatural narrative device, not a claim about actual local tides or coastal conditions.

### Investigation and puzzles

Target 5–7 main puzzles, based on audio recordings, photographs, documents, simple electrical systems and tide information. Puzzles must be readable without external guides and must not rely on obscure local knowledge.

### Horror pacing

Build tension through environmental anomalies, indirect manifestations, brief sightings and a small number of authored chase sequences. Avoid constant jumpscares.

## 8. Definitive proposed map — fictional composite geography

The campaign uses five compact playable zones arranged as a connected fictional coastal district. This is the definitive **production proposal** for the current scope, not a claim that these fictional places exist in real Maceió.

1. **Vila do Sal — arrival and neighborhood**
   - Visual inspiration: residential streets and everyday textures from the lagoon-facing and historic urban fabric.
   - Play space: one short street, a small square, a closed shopfront and one safe interior.
   - Gameplay: arrival, first clues, introduction to the recorder and local atmosphere.
   - Target: 10–20 minutes.

2. **Pousada Brisa Baixa — central hub**
   - Visual inspiration: older coastal guesthouses and historic buildings, with a fictional layout.
   - Play space: reception, two guest rooms, kitchen, service corridor and courtyard.
   - Gameplay: main investigation hub; family photographs, letters, first puzzle and route unlocks.
   - Target: 25–35 minutes.

3. **Cais das Pedras — port and fishing quay**
   - Visual inspiration: Jaraguá's port heritage and working waterfront, without copying a specific protected building.
   - Play space: short quay, boat shed, storage room and mooring area.
   - Gameplay: first direct entity encounter, sound-based navigation and a tide-gated route.
   - Target: 25–35 minutes.

4. **Baixio — exposed settlement**
   - Visual inspiration: reef coastline, shallow-water formations and lagoon/sea edge environments.
   - Play space: a compact route through exposed foundations, fictional house remains and a submerged street.
   - Gameplay: main tide-state sequence, environmental puzzles and major family revelation.
   - Target: 35–45 minutes.

5. **Abaixo — final chamber**
   - Visual inspiration: invented infrastructure beneath the exposed settlement; not a real archaeological site.
   - Play space: a small sequence of flooded passages and one central chamber.
   - Gameplay: final revelation, choice and three short ending variations using shared assets.
   - Target: 20–30 minutes.

### Connectivity and pacing

**Vila do Sal → Pousada Brisa Baixa ↔ Cais das Pedras → Baixio → Abaixo**

The guesthouse is the hub. A shortcut between the guesthouse and quay opens after the first investigation. Baixio is accessible only during the authored low-tide window. The final area is linear to protect pacing and keep the project achievable.

### Map production constraints

- No open world.
- Five zones maximum for the first release.
- Reuse modular building kits, props and materials.
- Use a few distant skyline / coastline views to communicate Maceió's coastal identity without building the whole city.
- Avoid exact reproduction of private homes or sensitive sites without permission.
- Confirm the final geographic references with local photo research and on-site observation where feasible.

See [MAPA.md](MAPA.md) for the zone-by-zone map brief and level-design checklist.

## 9. Campaign structure

| Section | Target time | Purpose |
|---|---:|---|
| Arrival / prologue | 10 min | Establish Helena, present-day Maceió and the message |
| Act I | 30 min | Explore Vila do Sal and investigate the guesthouse |
| Act II | 45 min | Reach the quay and solve the first major clues |
| Act III | 55 min | Explore Baixio and reveal the family connection |
| Finale | 30 min | Enter Abaixo and choose an ending |
| **Total** | **170 min** | Target runtime; validate through playtests |

Target 2–3 endings using shared spaces and assets rather than separate campaigns.

## 10. Technical direction — provisional

- Unreal Engine 5, Windows target.
- C++ for reusable core systems; Blueprints for authored interactions, triggers and iteration.
- First-person controller and interaction interface.
- Tide Manager with explicit state transitions and event dispatch.
- Investigation / evidence component.
- Horror Director for authored encounters.
- Local save/checkpoint system.
- UMG for menus, settings and minimal in-game UI.
- MetaSounds / spatial audio as appropriate.
- Git for source and text assets; Git LFS for approved large binary assets.

Do not add an online backend, multiplayer, procedural world generation or complex combat to the first release.

## 11. Initial content boundaries

**In scope:** one protagonist, one primary entity, five compact zones, 5–7 puzzles, 2–3 endings, Portuguese (Brazil) and English text.

**Out of scope for first release:** open world, multiplayer, crafting, extensive combat, branching companion systems, large crowds, fully simulated tides and console certification.

## 12. Production milestones

1. **Pre-production:** reference research, story outline, greybox, technical spike.
2. **Prototype:** first-person movement, interaction, flashlight, one tide transition.
3. **Vertical slice:** 15–20 minute polished sequence with final-quality lighting, audio and one encounter.
4. **Production:** remaining zones, puzzles, narrative and endings.
5. **Alpha / Beta:** full campaign playable; save, settings, accessibility and QA.
6. **Release preparation:** performance, localization, store materials, external playtests.

A 9–12 month schedule is a planning hypothesis only. Re-estimate after the team size, available hours and hardware are confirmed.

## 13. Key risks and mitigations

- **Scope growth:** lock the five-zone limit and validate every new feature against the 3-hour target.
- **Inexperienced game team:** build a vertical slice before full production.
- **Performance:** test on a defined minimum-spec PC from the first greybox.
- **Cultural inaccuracies:** research local history and consult Maceió / Alagoas residents.
- **Asset licensing:** track source, license and attribution for every external asset.
- **Narrative clarity:** test comprehension with players unfamiliar with Maceió.
- **Misrepresentation of real history:** keep all disappearances, supernatural events and family secrets clearly fictional.

## 14. Research references

Use these as starting points for cultural and historical research, not as sources for the fictional supernatural plot:

- [SECULT Alagoas — Histórico do município de Maceió](https://cultura.al.gov.br/municipios/historico-dos-municipios-alagoanos/342-historico-de-municipios/374-historico-do-municipio-de-maceio)
- [Prefeitura de Maceió — proteção ao patrimônio cultural](https://maceio.al.gov.br/noticias/iplam/minuta-do-novo-plano-diretor-de-maceio-amplia-protecao-ao-patrimonio-cultural)
- [UFAL — A territorialidade do patrimônio cultural do bairro do Jaraguá](https://www.repositorio.ufal.br/handle/riufal/2925)
- [IPHAN — Relatório de mapeamento do patrimônio imaterial em Alagoas](https://portal.iphan.gov.br/uploads/ckfinder/arquivos/Relatorio_final_mapeamento_alagoas_PNPI%281%29.pdf)

## 15. Open decisions

- Confirm protagonist's detailed background and exact family relationship.
- Validate the five-zone greybox and travel times.
- Choose exact fictional building layouts and visual references.
- Confirm team size, weekly availability and hardware budget.
- Define minimum PC specifications after the vertical slice.
- Validate the title and tagline before public marketing.
