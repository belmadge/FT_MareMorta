# Maré Morta — Definitive Map Proposal

**Project:** FT_MareMorta  
**Version:** 1.0  
**Status:** Proposed for greybox validation  
**Setting:** Contemporary, fictionalized Maceió, Alagoas

## Design intent

Build a compact, connected five-zone horror campaign inspired by Maceió's coastal and lagoon geography. The map should feel locally grounded through light, vegetation, building materials, boats, street details, sound and the relationship between city and water.

All playable districts and named buildings below are fictional. Real places are reference anchors only. This map is a game-design composition, not a geographically accurate street map.

## Macro layout

```text
                 [ VILA DO SAL ]
                        |
                        v
              [ POUSADA BRISA BAIXA ]
                        |
                 shortcut opens
                        |
                        v
                 [ CAIS DAS PEDRAS ]
                        |
                 low tide access
                        |
                        v
                    [ BAIXIO ]
                        |
                 one-way descent
                        |
                        v
                     [ ABAIXO ]
```

The guesthouse is the central hub. A shortcut between the guesthouse and quay opens after the first investigation. Baixio is gated by the authored low-tide state. Abaixo is the linear finale.

## Zone briefs

### A. Vila do Sal — arrival

**Reference blend:** lagoon-facing residential textures and historic urban fabric.

- One compact street, small square, closed shopfront and one accessible safe interior.
- Establish contemporary Maceió through signage style, tropical vegetation, humidity, pavement, utility infrastructure and distant water views.
- Introduce the voice message and first family clue.
- Avoid using real private addresses or identifiable residents.

**Gameplay beat:** safe exploration; teach movement, inspection and recorder playback.

### B. Pousada Brisa Baixa — hub

**Reference blend:** older coastal guesthouses and historic architecture, with a wholly fictional floor plan.

- Reception, two guest rooms, kitchen, service corridor and courtyard.
- Main evidence board / clue organization can be diegetic or represented through journal UI.
- Connects to Vila do Sal and later to Cais das Pedras.
- Revisit with altered audio, light and a small number of environmental changes.

**Gameplay beat:** first major family revelation and the first puzzle chain.

### C. Cais das Pedras — quay

**Reference blend:** Jaraguá port heritage and working waterfront, without copying a specific protected building.

- Short quay, boat shed, storage room and mooring area.
- Use ropes, buoys, weathered wood, metal, salt stains and harbor ambience.
- Keep boats static or on simple authored animation to control production scope.
- First direct sighting / encounter with the entity.

**Gameplay beat:** sound-based navigation and a tide-gated route.

### D. Baixio — exposed settlement

**Reference blend:** reef coastline, shallow-water formations and the lagoon/sea edge.

- A compact exposed route through fictional foundations, house remains and a submerged street.
- Distinctive silhouettes visible from the shore before the player can reach them.
- Low-tide access opens the route; rising tide changes the route and threat timing.
- Main sequence for environmental puzzles and the family's connection to the event.

**Gameplay beat:** signature tide sequence and major narrative reveal.

### E. Abaixo — final chamber

**Reference blend:** entirely invented underground / submerged infrastructure.

- Short flooded passage, one transition chamber and one central chamber.
- No claim that this is a real archaeological site or historical structure.
- Reuse materials and props from Baixio to keep asset scope small.
- Final decision and ending variants use the same room and cinematics with controlled differences.

**Gameplay beat:** final revelation and ending choice.

## Player flow and target time

| Zone | Target time | Main purpose |
|---|---:|---|
| Vila do Sal | 10–20 min | Arrival and tutorial |
| Pousada Brisa Baixa | 25–35 min | Hub and family investigation |
| Cais das Pedras | 25–35 min | First direct threat |
| Baixio | 35–45 min | Tide mechanic and major reveal |
| Abaixo | 20–30 min | Finale and choice |

The campaign target is approximately 170 minutes, with playtests ensuring the main path remains within three hours.

## Tide-state gating

| State | Access and presentation |
|---|---|
| Low | Exposed route to Baixio is open |
| Rising | Route warnings, water audio and threat escalation |
| High | Baixio access is closed; hub / quay routes remain |
| Falling | Used for authored transitions and selected return paths |

Use scripted triggers and clear player feedback. Do not strand the player or require waiting through a long real-time tide simulation.

## Greybox checklist

- [ ] Player can navigate all five zones without final art.
- [ ] Hub-to-quay shortcut is understandable.
- [ ] Baixio route is clearly readable and tide-gated.
- [ ] Player always receives warning before a route closes.
- [ ] Each zone has one memorable visual landmark.
- [ ] Main path playtest falls between 150 and 180 minutes after content implementation.
- [ ] No zone requires a unique large-scale asset set.
- [ ] Real-world reference photos are documented with source, date and usage permissions where relevant.
- [ ] Local cultural details are reviewed for accuracy and respect.

## Visual landmarks

1. **Vila do Sal:** a small square with a view toward water and a distinctive old streetlight.
2. **Pousada Brisa Baixa:** an internal courtyard with a rainwater cistern.
3. **Cais das Pedras:** a leaning mooring post and a boat shed with a broken roof.
4. **Baixio:** a row of exposed foundations and one unmistakable doorway standing in shallow water.
5. **Abaixo:** a circular chamber where water sounds appear to come from above and below at once.

## Production constraints

- Five zones maximum for first release.
- No open world or full-city recreation.
- Modular environment kit shared across zones.
- Distant skyline / coast cards and vista meshes instead of explorable city blocks.
- Fictional signage and business names.
- Do not reproduce protected buildings or private properties exactly without permission.
- The map must be validated with a greybox before final environment art begins.
