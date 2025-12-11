# [WORKING TITLE: AUTOGANG]
## Game Design Document

> *A man in a 1950s suit and tie stands atop a sedan in a flooded city, paddling toward shore with a broken signpost. Behind him, a convoy of desperate survivors follows.*

---

## High Concept

**Oregon Trail meets Mad Max** - A post-apocalyptic survival RPG where players lead a convoy of automobiles and survivors across a devastated American landscape, fleeing catastrophe and searching for safety.

---

## Core Vision

In a world where "some catastrophic something" has forced millions onto the roads, players must manage a growing gang of survivors, their vehicles, and precious resources while navigating dangers both natural and human.

The game explores themes of:
- Civilization's fragility
- Community in crisis
- The tension between survival and humanity
- The strange democracy of disaster (the businessman and the mechanic need each other now)

---

## Core Gameplay Loop

```
TRAVEL → ENCOUNTER → DECIDE → CONSEQUENCE → TRAVEL
   ↓                                            ↑
   └── RESOURCE MANAGEMENT (continuous) ────────┘
```

1. **Travel** between locations (consumes fuel, time, wears vehicles)
2. **Encounter** obstacles, opportunities, strangers, settlements
3. **Decide** how to handle each situation
4. **Consequence** - gain/lose resources, people, reputation
5. **Repeat** while managing the convoy's needs

---

## The Challenge

> "Make the travel between cities fun and exploring cities/towns/landmarks interesting"

This is the heart of the design problem. Solutions to explore:
- Dynamic event system during travel (not just "X days pass...")
- Meaningful choices with lasting consequences
- Characters with stories that unfold over time
- The road itself tells stories (abandoned cars, signs of what happened)
- Radio chatter, rumors, building a mental map of the world

---

## Resources

### People Resources
- **Health/HP** - Physical condition
- **Morale** - Mental state, affects performance
- **Hunger** - Need food regularly
- **Skills** - Class abilities + experience

### Convoy Resources
- **Fuel** - The lifeblood (consumed by travel)
- **Food** - Keeps people alive
- **Medicine** - Heals injuries, treats illness
- **Ammo** - For defense
- **Parts** - Vehicle repair and upgrades
- **Water** - Essential for survival
- **Trade Goods** - Barter economy

### Vehicle Resources
- **Condition** - Damage state
- **Fuel Capacity** - Range
- **Cargo Space** - What it can carry
- **Passenger Capacity** - How many people
- **Special Features** - Armor, weapons, etc.

---

## Character Classes

### Combat
- **Shooter** - Ranged combat specialist
- **Brawler** - Close combat, intimidation
- **Scout** - Reconnaissance, stealth

### Technical
- **Mechanic** - Vehicle repair
- **Engineer** - Upgrades, improvised solutions
- **Driver** - Vehicle handling, fuel efficiency

### Support
- **Doctor** - Major medical, surgery
- **Nurse** - First aid, ongoing care
- **Cook** - Food efficiency, morale boost

### Social
- **Trader** - Better barter deals
- **Leader** - Morale, group coordination
- **Diplomat** - Peaceful resolutions

### Specialist (Rare)
- *To be discovered through play...*

---

## Obstacles & Threats

### Environmental
- Flooding
- Wildfires
- Tornadoes
- Rock slides / Road collapse
- Extreme heat/cold
- Fuel shortage zones

### Human
- Hostile gangs / Raiders
- Desperate survivors (moral dilemmas)
- Corrupt "authorities"
- Cults
- Territorial settlements

### Mechanical
- Vehicle breakdowns
- Fuel contamination
- Parts scarcity

### Medical
- Injuries from combat/accidents
- Illness / Epidemics
- Psychological trauma

---

## Opportunities

- Recruit new survivors (each with backstory, skills, secrets)
- Salvage vehicles
- Discover supply caches
- Trade with settlements
- Find allies / Form alliances
- Learn information about safe zones
- Upgrade vehicles
- Rest and recover

---

## Encounter Design Philosophy

Every encounter should:
1. Present a meaningful choice
2. Have multiple valid approaches
3. Connect to the world's story
4. Potentially reveal character backstory
5. Feel emergent, not scripted

**Replayability through randomness** - Same game twice should never feel the same, but patterns and world logic should feel consistent.

---

## Locations

### Types
- **Cities** - High risk, high reward, complex exploration
- **Towns** - Medium encounters, trade opportunities
- **Landmarks** - Story moments, unique encounters
- **Road Events** - The journey itself
- **Camps** - Player-created rest stops

### What makes exploring interesting?
- Each location has history (what happened here?)
- Factions may control areas
- Resources vary by location type
- NPCs remember you
- Some locations change over time
- Hidden areas to discover

---

## Narrative Structure

### The Catastrophe
*[To be determined - could be revealed slowly through play]*
- Climate disaster?
- Economic collapse?
- Pandemic?
- War?
- Something stranger?

### The Goal
*[To be determined]*
- Reach a promised safe zone?
- Build a new settlement?
- Find someone/something?
- Simply survive as long as possible?

### Character Arcs
Each recruitable NPC has:
- A backstory (revealed over time)
- A personal goal
- Relationships to other possible NPCs
- A potential character arc

---

## Platform Considerations

| Platform | Pros | Cons |
|----------|------|------|
| Desktop (PC/Mac) | Full control, rich UI | Smaller audience |
| Mobile | Huge audience, pick-up-play | UI constraints, monetization pressure |
| Web | Accessible, cross-platform | Performance limits |
| Web MMO | Social, persistent world | Massive complexity |

**Current thinking:** Start simple, prove the concept, then scale.

---

## Inspirations

- **Oregon Trail** - Resource management, random events, party survival
- **Mad Max** - Automotive post-apocalypse aesthetic
- **FTL** - Roguelike structure, meaningful choices
- **Banner Saga** - Caravan management, story weight
- **The Road** (novel/film) - Emotional weight, moral complexity
- **Station Eleven** - Civilization's artifacts in collapse

---

## Open Questions

1. What is the catastrophe? (Or do we leave it ambiguous?)
2. Is there a win condition or is it endless survival?
3. Turn-based or real-time?
4. Single player, co-op, or MMO?
5. Art style?
6. What's the NAME?

---

## Development Phases

### Phase 1: Design
- [ ] Finalize core mechanics on paper
- [ ] Create character roster (20-50 unique NPCs?)
- [ ] Map the world (abstract or geographic?)
- [ ] Write encounter templates
- [ ] Paper prototype / play testing

### Phase 2: Prototype
- [ ] Minimal viable game loop
- [ ] Basic UI
- [ ] Core systems working
- [ ] Playable from start to "end"

### Phase 3: Content
- [ ] Full NPC roster with stories
- [ ] Complete location set
- [ ] All encounter types
- [ ] Balancing

### Phase 4: Polish
- [ ] Art and sound
- [ ] UI/UX refinement
- [ ] Extended testing
- [ ] Platform optimization

### Phase 5: Release
- [ ] Manual / Tutorial
- [ ] Distribution
- [ ] Community building

---

*Document started: December 11, 2025*
*Last updated: December 11, 2025*
