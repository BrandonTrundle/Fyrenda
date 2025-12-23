```statblock
# ===== BASIC INFO =====
name: Mushroom Stalker
image: Utility/Images/BeastiaryImages/MushroomStalker.jpeg
layout: 5e-wide
width: 1100
image_height: 300

size: Medium
type: Plant
alignment: Unaligned

ac: 15 (natural armor)
hp: 102
hit_dice: 12d8+48

speed: 30 ft., climb 20 ft.

# ===== ABILITY SCORES =====
stats:
  - 16
  - 18
  - 18
  - 6
  - 14
  - 6

# ===== SAVES =====
saves:
  strength: 5
  dexterity: 7
  constitution: 7
  intelligence: 0
  wisdom: 4
  charisma: 0

# ===== SKILLS =====
skillsaves:
  perception: 4
  stealth: 9
  insight: 2

damage_resistances: necrotic, poison; bludgeoning from nonmagical attacks
damage_immunities: —
condition_immunities: blinded, charmed, frightened, poisoned

senses: blindsight 30 ft., darkvision 60 ft., passive Perception 14
languages: —
cr: "6"

# ===== TRAITS =====
traits:
  - name: Spore Shroud
    desc: |
      The Stalker is surrounded by a cloud of faint spores. A creature that begins its turn within 5 feet of it must succeed on a DC 15 Constitution saving throw or be poisoned until the start of its next turn.

  - name: Silent Predator
    desc: |
      The Stalker has advantage on Dexterity (Stealth) checks made to hide in dim light, darkness, or foliage.

# ===== ACTIONS =====
actions:
  - name: Multiattack
    desc: |
      The Mushroom Stalker makes two Claw attacks.

  - name: Claw
    desc: |
      Melee Weapon Attack: +7 to hit, reach 5 ft., one target.
    attack_bonus: 7
    damage:
      - dice: 2d6
        bonus: 4
        type: slashing

  - name: Spore Burst
    desc: |
      The Stalker releases a burst of toxic spores in a 15-foot radius. Creatures in the area must make a DC 15 Constitution saving throw or take 3d8 poison damage and be poisoned for 1 minute. A poisoned creature repeats the save at the end of each of its turns.
    save_dc: 15
    save_ability: constitution

  - name: Neurotoxic Sting (Recharge 5–6)
    desc: |
      The Stalker strikes with a spore-tipped tendril. The target must succeed on a DC 15 Constitution saving throw or take 4d6 poison damage and become incapacitated until the end of its next turn.
    save_dc: 15
    save_ability: constitution
    damage:
      - dice: 4d6
        type: poison

  - name: Fungal Step
    desc: |
      The Stalker moves up to half its speed and does not provoke opportunity attacks.
    attack_bonus: 0

# ===== LEGENDARY ACTIONS =====
legendary_actions:
  - name: Skitter
    desc: |
      The Stalker moves 10 feet without provoking opportunity attacks.
    roll:
      - skill: stealth

  - name: Sudden Claw
    desc: |
      The Stalker lashes out.
    attack:
      bonus: 7
      damage_dice: 1d6
      damage_bonus: 4
      damage_type: slashing

  - name: Spore Lash
    desc: |
      A cloud of spores erupts. One creature within 10 feet must succeed on a DC 15 Constitution saving throw or take 2d6 poison damage.
    save_dc: 15
    save_ability: constitution
    damage:
      - dice: 2d6
        bonus: 0
        type: poison
```

### ⭐ **Visual Description**

A tall, spindly creature moves with unnatural grace, its limbs elongated like skeletal branches. Mushrooms pulse along its back, glowing faintly as spores drift from its joints. Its head is little more than a stalk topped with a trembling fungal cap that expands and contracts like a breathing lung. When it moves, the forest air ripples with dust-like spores.