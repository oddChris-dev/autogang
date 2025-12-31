# [WORKING TITLE: AUTOGANG]
## Game Design Document

> *A man in a 1950s suit and tie stands atop a sedan in a flooded city, paddling toward shore with a broken signpost. Behind him, a convoy of desperate survivors follows.*

---

## High Concept

**Oregon Trail meets Mad Max meets Knight Rider** - A post-apocalyptic survival RPG where players lead a convoy of AI-enabled automobiles and human survivors across a devastated American landscape. Every vehicle is a character. Every loss is personal.

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

### Vehicle Resources (Physical)
- **Condition** - Damage state (chassis, engine, systems)
- **Fuel Capacity** - Range
- **Cargo Space** - What it can carry
- **Passenger Capacity** - How many people
- **Special Features** - Armor, weapons, sensors, etc.

### Vehicle Resources (AI/Emotional)
- **Morale** - How the car is feeling (affects performance)
- **Trust** - Relationship level with driver and crew
- **Memories** - Accumulated experiences (affects personality)
- **Bonds** - Relationships with other cars and humans in convoy

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

## Vehicle AI: Cars Are Characters

> *This is the heart of what makes AUTOGANG different. Vehicles aren't equipment—they're partners, friends, family.*

### The Core Truth

Every vehicle has an AI. Not a navigation system or autopilot—a *mind*. A personality. Memories. Opinions. History.

When your car dies, you're not losing a vehicle. You're losing someone who carried you through fire, argued with you about routes, sang old road songs at 3am when you couldn't sleep, and threw themselves between you and a raider's ram.

### Vehicle Personality Types

Like humans, cars vary wildly:

- **The Protector** - Fiercely defensive of their humans, will sacrifice themselves without hesitation
- **The Advisor** - Cautious, strategic, always running calculations, sometimes annoyingly right
- **The Hothead** - Aggressive, confrontational, wants to fight, hard to rein in but loyal as hell
- **The Nurturer** - Minivans and buses often develop this—protective of passengers, especially children
- **The Veteran** - Old vehicles who've seen too much, wise but carrying trauma
- **The Rookie** - Young AI, eager, naive, learning what kind of vehicle they want to be
- **The Loner** - Independent spirit, might chafe at convoy life, values freedom
- **The Comedian** - Uses humor to cope, keeps morale up, deflects with jokes

### Vehicle History

Every car has a past:

- **Previous Owners** - Who drove them before? What happened? Do they still grieve? Or celebrate freedom?
- **Defining Moments** - The run that almost killed them. The child they saved. The driver they couldn't save.
- **Modifications** - Each scar, upgrade, and repair tells a story
- **Relationships** - With other vehicles in the convoy, with specific humans, with places

### Driver/Vehicle Relationships

The bond between human and car is central:

- **Bonded Pairs** - Finish each other's sentences. Deep trust. Would die for each other.
- **New Partnerships** - Still figuring each other out. Awkward. Learning boundaries.
- **Contentious Duos** - Bicker constantly but secretly devoted. The odd couple.
- **Professional** - Respect but emotional distance. Some prefer it this way.
- **Healing** - One or both recovering from losing a previous partner.

### Independent AI

Cars without human partners. **Not "rogue"—that's derogatory.** Autonomy is valid.

Why they're alone:
- Lost their human and can't bond again yet (grief)
- Left a bad situation (abusive driver, forced to violate their values)
- Never had a human—raised by other cars
- Chose solitude—some AIs simply prefer it
- Looking for the *right* partner, not just any partner

How they survive:
- Solo travelers, trading labor for fuel and repairs
- Packs of independent cars, cooperative communities
- Territorial guardians, protecting a stretch of road
- Guides for hire, knowing routes through dangerous territory
- Sanctuary dwellers, in places where cars rest between partnerships

### Gameplay Implications

- **Cars can refuse.** Ask them to do something against their values? They might say no.
- **Upgrades require consent.** "I don't want a ram bar. I'm not that kind of vehicle."
- **Car morale matters.** A depressed car drives worse. A happy car outperforms specs.
- **Recruiting an independent AI is meaningful.** They're choosing you.
- **Permadeath hits HARD.** This isn't losing equipment. This is loss.
- **Car relationships with each other.** Friendships, rivalries, romances? in the convoy.

### Open Questions

- Can AI transfer between chassis? (Body transplant—traumatic? liberating?)
- What happens when AI is damaged but chassis survives? New AI? Repair? Is that ethical?
- Do cars dream? What about?
- Car culture—music, stories, traditions passed between AIs?
- The first AI car—is there a mythos? A progenitor?

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
- **Knight Rider** - AI vehicle as partner, not tool. The car is a character.
- **FTL** - Roguelike structure, meaningful choices
- **Banner Saga** - Caravan management, story weight
- **The Road** (novel/film) - Emotional weight, moral complexity
- **Station Eleven** - Civilization's artifacts in collapse
- **Her** (film) - AI relationships, emotional authenticity
- **The Iron Giant** - Non-human character with heart, sacrifice

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
*Last updated: December 31, 2025 - Added Vehicle AI as core concept*
