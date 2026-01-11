# Bacon Cat Platformer - Game Design Document

**Version:** 0.1  
**Last Updated:** January 11, 2026  
**Author:** Elvis Sanchez Robles

---

## 1. Game Overview

### High Concept
A 2D platformer where you play as Bacon Cat, a brave feline hero who must recover the legendary Sandwich from the Evil Boss of the Doggo Clan named Dr. Woofer. Bacon Cat will have to use his incredible mind and bacon powers to solve puzzles and travel acrross multiple lands to take back the legendary sandwich stolen by the Doggo Clan. 

### Genre
- Primary: 2D Platformer
- Secondary: Puzzle-Platformer
- Tertiary: Story/Narrative Adventure

### Target Audience
- Age: 10+
- Players who enjoy:  Celeste, Hollow Knight, Ori and the Blind Forest, indie platformers
- Casual to moderate difficulty

### Unique Selling Points (USP)
1. **Bacon Cat** - Memorable, unique protagonist
2. **Story + Puzzles** - Not just jumping, but thinking
3. **Charm** - Lighthearted tone with heart
4. **Mentally Stimulant Game** - Not boring or repetitive, will have to use mind to solve puzzles and progress throughout the world

---

## 2. Story & Setting

### Story Synopsis
[Write 2-3 paragraphs about Bacon Cat's adventure]
Bacon Cat and his friends were enjoying a chill day eating breakfast at the Purrville Plaza where a bunch of kittens enjoyed each others' company. This day the Doggo Clan decided to attack Purrville and stole the legendary Sandwich which was the primary source of energy in Purrville. They also took many kittens as hostages and scattered them across multiple areas of the DoggoLand (this would be the worlds). Bacon Cat which was the only not taken kitten will have to save Purrville.


### Main Characters
- **Bacon Cat**: A goofy but incredibly smart feline hero with a heart of gold and a belly full of courage. Despite his lighthearted nature, he's the only kitten who escaped the Doggo Clan's raid on Purrville. As he progresses through his journey, he unlocks powerful bacon-based abilities including throwing bacon strips as projectiles, double jump, rainbow dash, and wall slide. His only weakness? An inexplicable hatred of Tuesdays. Personality: Brave, quick-witted, determined, uses humor to cope with danger.
- **Supporting Characters**: 
  - **The Lost Kittens**: Fellow residents of Purrville scattered across DoggoLand as hostages. Each rescued kitten gives Bacon Cat hints, unlocks new abilities, or provides comic relief. They represent the hope of Purrville.
  - **Elder Whiskers**: The wise old cat who appears in visions to guide Bacon Cat on his quest (tutorial NPC).
- **Antagonist**: 
  - **Dr. Woofer**: The brilliant but evil mastermind behind the Doggo Clan. He stole the legendary Sandwich to drain Purrville's energy and expand his DoggoLand empire. Personality: Cunning, dramatic, obsessed with proving dogs are superior to cats.
  - **The Doggo Clan**: Various dog enemies including Pug Guards, Retriever Runners, Bulldog Brutes, and Chihuahua Snipers.

### World/Setting
The game takes place across **DoggoLand**, the territory controlled by the Doggo Clan. Each world represents a different region where kittens are being held captive:

- **World 1: Bark Boulevard** - Urban streets and alleyways with fire hydrants, mailboxes, and doghouses. Theme: City/Industrial. Introduces basic mechanics. (Levels 1-3)
- **World 2: Howling Heights** - Mountain peaks and rocky cliffs with bone bridges and dog treat platforms. Theme: Mountain/Vertical. Introduces wall sliding and precision jumping. (Levels 4-6)
- **World 3: Ruff Rapids** - Water-themed world with floating kibble platforms and hydro-powered puzzles. Theme: Aquatic/Puzzle-heavy. (Levels 7-9)
- **World 4: Dr. Woofer's Laboratory** - High-tech facility filled with laser grids, moving platforms, and scientific contraptions. Theme: Sci-fi/Boss. Final confrontation with Dr. Woofer. (Levels 10-12)

---

## 3. Core Gameplay Mechanics

### Movement
- **Walk/Run**: Smooth left/right movement with acceleration. Running speed: 200 pixels/second
- **Jump**: Initial single jump (height: 3 tiles). **Double Jump** unlocked in World 2 after rescuing 3 kittens
- **Wall Slide**: Unlocked in World 2. Bacon Cat can slide down walls and wall-jump to climb vertical sections
- **Rainbow Dash**: Unlocked in World 3. Short horizontal burst of speed with invincibility frames (limited uses per level or cooldown) 

### Combat
- **Bacon Projectiles**: Primary attack. Bacon Cat throws bacon strips that arc through the air. Unlocked after first kitten rescue in World 1. Ammo: 10 strips (refills at checkpoints)
- **Stomp Attack**: Jump on enemies from above to defeat them. Works on smaller enemies only
- **Rainbow Dash**: When unlocked, can dash through enemies for damage during invincibility
- **Enemy Behavior**: Most enemies patrol set paths. Some respond to Bacon Cat's presence. Boss fights require pattern recognition and use of all abilities 

### Puzzle Mechanics
1. **Switches and Doors**: Hit switches with bacon projectiles or stomp them to open doors and activate platforms
2. **Movable Blocks**: Push/pull kibble blocks to reach higher areas, block lasers, or weigh down pressure plates
3. **Laser Grids**: Introduced in World 3-4. Use mirrors (movable blocks) to redirect lasers and disable barriers
4. **Kitten Cages**: Find keys or solve puzzles to free captured kittens. Each rescue unlocks story dialogue and sometimes new abilities
5. **Bone Bridges**: Certain bridges made of bones collapse when stepped on - must dash or jump quickly
6. **Timed Platforms**: Platforms that appear/disappear on timers, requiring precision and planning 

### Collectibles
- **Bacon Strips**: Main collectible (100 per level?)
- **Cat Coins**: Currency for unlockables? 
- **Hidden Stars**: 3 per level for completionists

---

## 4. Level Design Philosophy

### Level Structure
- **8-12 levels total** for first version
- Each level:  3-5 minutes to complete
- 3 levels per world/theme

### Difficulty Curve
- Levels 1-2: Tutorial, introduce one mechanic at a time
- Levels 3-5: Combine 2 mechanics
- Levels 6-8: Full challenge, all mechanics
- Levels 9-10: Master levels

### Puzzle Integration
- Each level has 2-3 puzzle sections
- Puzzles block progress but aren't time-based
- Puzzles teach player new skills

---

## 5. Art Style

### Visual Direction
- **Style**: Colorful pixel art with a modern, polished aesthetic
- **Color Palette**: 
  - Purrville/UI: Warm oranges, browns (bacon colors), soft purples and blues
  - DoggoLand: Each world has distinct palette (urban greys, mountain blues, water teals, lab greens)
  - High contrast for readability
- **Reference Games**: Celeste (clean pixel art), Shovel Knight (retro charm), Ori (environmental beauty)
- **Animation**: Smooth character animations with personality (tail swishes, ear twitches, bacon flapping)

### Character Design
- **Bacon Cat**: Orange/brown tabby cat with bacon-striped pattern on back. Large expressive eyes. Small red cape (hero look). Size: 16x16 pixels base, 32x32 with animations. Idle animation shows confident stance with slight tail swish
- **Enemies**: 
  - **Pug Guards**: Round, slow, patrol guards wearing helmets
  - **Retriever Runners**: Fast, chase players when spotted
  - **Bulldog Brutes**: Large, tough, require multiple hits
  - **Chihuahua Snipers**: Small, shoot projectiles from distance
  - **Dr. Woofer**: Tall scientist dog in lab coat with goggles, mechanical arms

---

## 6. Audio

### Music Style
- **Genre**: Upbeat chiptune with modern production (think Shovel Knight meets Celeste)
- **World Themes**: 
  - World 1 (Bark Boulevard): Energetic, urban beats
  - World 2 (Howling Heights): Epic, climbing intensity
  - World 3 (Ruff Rapids): Flowing, aquatic melodies
  - World 4 (Laboratory): Electronic, tense boss music
- **Menu Music**: Calm, welcoming tune with bacon-cooking sizzle sounds subtly in background
- **Emotional Moments**: Softer piano for kitten rescue scenes and story beats

### Sound Effects
- Jump, land, collectible pickup
- UI sounds
- Environmental sounds

---

## 7. User Interface

### HUD (Heads-Up Display)
- **Health**: 3 hearts (cat paw prints). Can find +1 heart upgrades hidden in levels
- **Bacon Ammo**: Counter showing remaining bacon projectiles (10 max)
- **Collectible Counter**: Bacon strips collected / total (e.g., "45/100")
- **Lives**: 3 lives per level (restart from checkpoint if lost)
- **Kitten Counter**: Shows kittens rescued in current world (e.g., "2/3 kittens")
- **Timer**: Optional speedrun timer, hidden by default, can toggle in options

### Menus
- Main Menu:  Play, Options, Quit
- Pause Menu: Resume, Restart, Options, Main Menu
- Level Select (unlock as you progress)

---

## 8. Technical Specifications

### Engine & Tools
- **Engine**: Godot 4.x
- **Language**: GDScript
- **Art**: [Aseprite/Krita/etc.]
- **Audio**: [Your tools]

### Target Platforms
- Primary: PC (Windows, Linux, Mac)
- Secondary: Web (itch.io HTML5)
- Future: Mobile? 

### Target Resolution
- **Base Resolution**: 640x360 (16:9 ratio) for crisp pixel art
- **Scaled to**: 1920x1080 (3x integer scaling for pixel-perfect display)
- **Supports**: Windowed, fullscreen, and borderless modes
- **UI Scaling**: Maintains pixel-perfect scaling on different displays

---

## 9. Scope & Features

### MVP (Minimum Viable Product) - Version 1.0
- [ ] 12 playable levels (3 per world)
- [ ] Core movement (walk, jump, wall slide, dash)
- [ ] Combat system (bacon projectiles, stomp)
- [ ] 4-5 puzzle mechanics (switches, movable blocks, kitten cages, lasers, timed platforms)
- [ ] All 4 worlds with distinct themes
- [ ] Story cutscenes (intro, world transitions, ending)
- [ ] 12 kittens to rescue (1 per level)
- [ ] Main menu, pause menu, and level select
- [ ] Full sound effects and music for all worlds
- [ ] Basic particle effects and screen shake

### Nice-to-Have (Post-MVP)
- [ ] Double jump ability
- [ ] Boss fights
- [ ] Speedrun timer
- [ ] Achievements
- [ ] More levels

### Out of Scope (Not for v1.0)
- Multiplayer
- Level editor
- Full voice acting
- Mobile release

---

## 10. Development Milestones

| Phase | Duration | Deliverable |
|-------|----------|-------------|
| Pre-Production | 3 weeks | GDD, Art concepts, Prototype |
| Prototyping | 4 weeks | Working movement, 1 test level |
| Vertical Slice | 5 weeks | 1 complete level with all features |
| Production | 12 weeks | All 8 levels, full game |
| Polish | 4 weeks | Bug fixes, juice, balance |
| Launch Prep | 3 weeks | Marketing, store pages |

**Total: ~28-30 weeks**

---

## 11. Success Metrics

### Development Goals
- Complete and ship by [TARGET DATE]
- Stay within scope
- Learn Godot thoroughly

### Launch Goals
- 100 downloads in first month
- 10+ positive reviews
- Build social media following (500+ followers)
- Recoup $0 costs (if free) or $100-500 revenue

---

## Notes & Ideas

[Use this section to brainstorm]
- **Cool puzzle idea**: Tuesday level - Since Bacon Cat hates Tuesdays, a special challenge level where everything is slightly harder or inverted controls?
- **Story beat**: Mid-game revelation - Dr. Woofer was once friends with Elder Whiskers before turning evil. The Sandwich was meant to be shared.
- **Character ability**: Super Bacon Mode - Temporary power-up after rescuing certain kittens, makes Bacon Cat invincible with unlimited bacon throws
- **Level theme**: Hidden "Purrville Memories" bonus levels showing Bacon Cat's peaceful life before the invasion
- **Easter egg**: Scattered comic panels throughout levels telling backstory of the Doggo Clan
- **Collectible purpose**: 100% bacon collection in a level unlocks concept art or developer commentary
- **Difficulty option**: "Casual Cat" mode (more checkpoints, more health) vs "Heroic Cat" mode (fewer checkpoints, one-hit deaths) 

---

**This is a living document! ** Update as you develop and learn what works. 