# Maré Morta — Game Design Document

**Studio:** FerroTech Game Studio  
**Status:** Pre-production / concept draft  
**Version:** 0.1  
**Date:** 2026-11-14  
**Target:** Windows PC / Steam  
**Engine target:** Unreal Engine 5  
**Genre:** First-person psychological survival horror  
**Target playtime:** 2–3 hours  
**Players:** Single-player

> **Working tagline:** As águas guardam o que a cidade esqueceu.

## 1. High concept

A first-person psychological horror game set in a fictionalized version of Maceió, Alagoas. During an anomalous low tide, forgotten structures and fragments of the city's past emerge from the water. The protagonist returns to investigate a family disappearance and discovers that the phenomenon is connected to the city's coastal and lagoon landscapes.

The game uses real Maceió as cultural and visual inspiration, but its characters, supernatural events, locations, timeline and central mystery are fictional.

## 2. Creative pillars

1. **A distinctly Alagoan sense of place:** coastal light, reefs, lagoon landscapes, fishing culture, port heritage, local architecture, sounds and everyday details.
2. **Environmental storytelling:** clues in spaces, objects, recordings and changes in the landscape.
3. **Tide as progression:** water level changes access, visibility, sound and threat states.
4. **Psychological tension over combat:** avoidance, observation, uncertainty and carefully paced encounters.
5. **Compact premium experience:** a focused 2–3 hour campaign with a small number of highly authored spaces.

## 3. Setting and cultural references

The fictional setting draws from several real Maceió references:

- **Jaraguá:** historic port district, warehouses/trapiches and preserved architecture.
- **Lagoa Mundaú and its channels:** lagoon routes, fishing boats, mangroves and communities whose lives are connected to the water.
- **Pontal da Barra:** fishing and traditional craft references, including local ways of life and landscape.
- **Pajuçara and the reef coastline:** natural pools, reefs and the contrast between inviting shallow water and the open sea.
- **Centro and Bebedouro:** historic urban textures and the city's relationship with lagoon geography.

These references are not a literal map. The game will combine and fictionalize them into a coherent playable geography. Avoid presenting invented disasters, disappearances or supernatural claims as real local history. Treat residents and local culture respectfully; consult local people and sources during research.

## 4. Logline and narrative premise

After receiving an impossible voice message apparently recorded by her missing mother, Helena returns to a fictional coastal district of Maceió. An extreme low tide exposes a route to structures absent from every map. As the water returns, Helena uncovers a hidden family history and a presence that seems to remember the city differently from the living.

**Narrative rule:** the supernatural should remain partly ambiguous. Players should understand the emotional truth and immediate stakes without receiving a complete scientific explanation.

## 5. Main characters — provisional

- **Helena:** protagonist; returns to investigate the message and her mother's disappearance.
- **Antônio:** local fisherman and reluctant source of information.
- **Lúcia:** Helena's mother; present through recordings, objects and memories.
- **The Drowned (working name):** an entity glimpsed near exposed structures. Its design and origin remain deliberately incomplete.

Names, ages, relationships and final character biographies require narrative review.

## 6. Gameplay

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

A Tide Manager broadcasts state changes to level access, environmental presentation, audio and the horror director. Transitions should be scripted and predictable enough for level design and QA.

### Investigation and puzzles

Target 5–7 main puzzles, based on audio recordings, photographs, documents, simple electrical systems and tide information. Puzzles must be readable without external guides and must not rely on obscure local knowledge.

### Horror pacing

Build tension through environmental anomalies, indirect manifestations, brief sightings and a small number of authored chase sequences. Avoid constant jumpscares.

## 7. Level plan — fictional composite map

1. **Arrival / Vila das Conchas:** compact street, small square and first safe interior.
2. **Pousada Mar Azul:** central hub with reception, rooms, kitchen and service spaces.
3. **Porto Velho:** docks, boats and storage sheds; first direct threat.
4. **Exposed settlement:** fictional structures revealed by the low tide; major exploration sequence.
5. **The Below:** compact final underground / submerged space.

The level is interconnected but not open-world. Reuse modular architecture and keep the number of unique interior kits limited.

## 8. Campaign structure

| Section | Target time | Purpose |
|---|---:|---|
| Arrival / prologue | 10 min | Establish protagonist, place and message |
| Act I | 30 min | Learn the hub and investigate the inn |
| Act II | 45 min | Reach the exposed settlement and solve core puzzles |
| Act III | 55 min | Escalate threat and reveal family connection |
| Finale | 30 min | Final sequence and ending choice |
| **Total** | **170 min** | Target runtime; validate through playtests |

Target 2–3 endings using shared spaces and assets rather than separate campaigns.

## 9. Technical direction — provisional

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

## 10. Initial content boundaries

**In scope:** one protagonist, one primary entity, five compact zones, 5–7 puzzles, 2–3 endings, Portuguese (Brazil) and English text.

**Out of scope for first release:** open world, multiplayer, crafting, extensive combat, branching companion systems, large crowds, fully simulated tides and console certification.

## 11. Production milestones

1. **Pre-production:** reference research, story outline, greybox, technical spike.
2. **Prototype:** first-person movement, interaction, flashlight, one tide transition.
3. **Vertical slice:** 15–20 minute polished sequence with final-quality lighting, audio and one encounter.
4. **Production:** remaining zones, puzzles, narrative and endings.
5. **Alpha / Beta:** full campaign playable; save, settings, accessibility and QA.
6. **Release preparation:** performance, localization, store materials, external playtests.

A 9–12 month schedule is a planning hypothesis only. Re-estimate after the team size, available hours and hardware are confirmed.

## 12. Key risks and mitigations

- **Scope growth:** lock the five-zone limit and validate every new feature against the 3-hour target.
- **Inexperienced game team:** build a vertical slice before full production.
- **Performance:** test on a defined minimum-spec PC from the first greybox.
- **Cultural inaccuracies:** research local history and consult Maceió / Alagoas residents.
- **Asset licensing:** track source, license and attribution for every external asset.
- **Narrative clarity:** test comprehension with players unfamiliar with Maceió.

## 13. Research references

Use these as starting points for cultural and historical research, not as sources for the fictional supernatural plot:

- [SECULT Alagoas — Histórico do município de Maceió](https://cultura.al.gov.br/municipios/historico-dos-municipios-alagoanos/342-historico-de-municipios/374-historico-do-municipio-de-maceio)
- [Prefeitura de Maceió — proteção ao patrimônio cultural](https://maceio.al.gov.br/noticias/iplam/minuta-do-novo-plano-diretor-de-maceio-amplia-protecao-ao-patrimonio-cultural)
- [UFAL — A territorialidade do patrimônio cultural do bairro do Jaraguá](https://www.repositorio.ufal.br/handle/riufal/2925)
- [IPHAN — Relatório de mapeamento do patrimônio imaterial em Alagoas](https://portal.iphan.gov.br/uploads/ckfinder/arquivos/Relatorio_final_mapeamento_alagoas_PNPI%281%29.pdf)

## 14. Open decisions

- Confirm protagonist's background and family relationship.
- Choose the exact fictional geography and how it combines real references.
- Decide whether the story occurs in present-day Maceió or an alternate period.
- Confirm team size, weekly availability and hardware budget.
- Define minimum PC specifications after the vertical slice.
- Validate the title and tagline before public marketing.
