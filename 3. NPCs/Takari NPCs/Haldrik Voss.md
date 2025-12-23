```statblock
# ===== BASIC INFO =====
name: Haldrik Voss
image: Utility/Images/NPC Images/HaldrikVoss.jpeg
layout: 5e-wide
width: 1100
image_height: 250

size: Medium
type: humanoid
race: Human
class: Logistics Magnate
alignment: Lawful Neutral

ac: 13
hp: 27
hit_dice: 6d8

speed: 30 ft.

# ===== ABILITY SCORES =====
stats:
  - 10
  - 12
  - 12
  - 16
  - 14
  - 15

# ===== SAVES =====
# Only list if proficient or significant modifier
saves:
  intelligence: +5
  wisdom: +4
  charisma: +4

# ===== SKILLS =====
skillsaves:
  persuasion: +4
  deception: +4
  insight: +4
  intimidation: +3
  perception: +4
  stealth: +2
  athletics: +0
  arcana: +3
  history: +5
  religion: +2
  investigation: +5

# ===== ACTIONS (OPTIONAL COMBAT) =====
actions:
  - name: Dagger
    desc: |
      Melee Weapon Attack: +3 to hit, reach 5 ft., one target.
    attack_bonus: 3
    damage:
      - dice: 1d4
        bonus: 1
        type: piercing

  - name: Light Crossbow
    desc: |
      Ranged Weapon Attack: +3 to hit, range 80/320 ft., one target.
    attack_bonus: 3
    damage:
      - dice: 1d8
        bonus: 1
        type: piercing

  - name: Command the Flow (Recharge 5-6)
    desc: |
      One creature within 60 ft. that can hear him must succeed on a DC 13 Wisdom saving throw or be compelled to move up to half its speed in a direction he chooses without provoking opportunity attacks.
    save_dc: 13
    save_ability: Wisdom
    damage:
      - dice: 0
        type: none

# ===== REACTIONS =====
reactions:
  - name: Contingency Orders
    desc: |
      When a creature he can see makes an attack against him, he can impose disadvantage on that attack by calling for a sudden diversion. Usable once per short rest.

# ===== LEGENDARY ACTIONS (OPTIONAL) =====
legendary_actions:
  - name: None
    desc: |
      None.

  - name: None
    desc: |
      None.

# ===== PASSIVE STATS =====
passive_senses:
  perception: 14
  insight: 14

languages: Common, Dwarvish
cr: ""
```

##  Physical Description
A lean, middle aged man with slate-gray eyes and a severe jaw kept clean shaven. His dark hair is swept back and held with a bronze clasp, with a single silvering streak at the temple. He dresses in layered traveling coats of charcoal and rust, each seam reinforced, each pocket labeled with tiny stitched marks. His hands are ink-stained and callused from crates and ledgers alike, and a small brass timepiece hangs from his belt. He smells faintly of lamp oil, cold metal, and dusted parchment, and his voice is low, precise, and unhurried.

##  Roleplay Info
personality_traits: 
  Calm, methodical, and sparing with words. Tracks details others miss and expects the same discipline from those around him.

ideals: 
  Continuity. A city survives when the flow never stops, no matter the cost of keeping it moving.

bonds: 
  Bound to the Lumenfell supply routes, the warehouse masters who keep them running, and the consortium ledgers that prove his worth.

flaws: 
  Treats people like parts in a machine and underestimates emotional reactions he cannot price or predict.

goals: 
  Short term: secure exclusive control of the Lumenfell passes before the Council imposes new restrictions. Long term: make Takari dependent on his distribution network beyond repair.

background: 
  A veteran logistics magnate who built the modern ore pipeline, controlling chokepoints, storage, and transport with ruthless efficiency.

#  SOCIAL ABILITIES 
  - name: Logistics Leverage
    desc: 
      He can reroute supplies or delay shipments with a word. When bargaining over resources, he gains advantage on Persuasion or Intimidation checks.

  - name: Ledger Recall
    desc: 
      After 10 minutes of review, he can cite a contract clause or shipping record with exacting precision, granting advantage on Investigation checks about trade or transport.
