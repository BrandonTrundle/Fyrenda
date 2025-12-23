```statblock
# ===== BASIC INFO =====
name: Dreambound Executioner
image: Utility/Images/Bad Guys/MasterCultist.jpeg
layout: 5e-wide
width: 1100
image_height: 300

size: Large
type: Humanoid (cultist)
alignment: Chaotic Evil

ac: 18
hp: 180
hit_dice: 19d10+76

speed: 35 ft.

# ===== ABILITY SCORES =====
# STR, DEX, CON, INT, WIS, CHA
stats:
  - 22
  - 12
  - 19
  - 8
  - 12
  - 10

# ===== SAVES =====
# Set only bonuses that differ from ability mod
saves:
  strength: +11
  constitution: +9
  wisdom: +6

# ===== SKILLS =====
skillsaves:
  perception: +6
  intimidation: +5
  athletics: +11

damage_resistances: psychic; bludgeoning, piercing, and slashing from nonmagical attacks
damage_immunities: —
condition_immunities: frightened

senses: darkvision 60 ft., passive Perception 16
languages: Common, Deep Speech
cr: "10"

# ===== TRAITS =====
traits:
  - name: Vorpal Menace
    desc: |
      The Dreambound Executioner wields a cursed vorpal greatsword. On a natural 20, the attack automatically scores a critical hit. If the target is not immune to decapitation and has 100 hit points or fewer, it must succeed on a DC 17 Constitution saving throw or be decapitated and instantly reduced to 0 hit points.

  - name: Relentless Advance
    desc: |
      The Executioner ignores difficult terrain and has advantage on saving throws against being restrained or knocked prone.

  - name: Headman’s Focus
    desc: |
      At the start of its turn, the Executioner chooses one creature it can see within 30 feet. Until the start of its next turn, the Executioner has advantage on attack rolls against that creature.

# ===== ACTIONS =====
actions:
  - name: Multiattack
    desc: |
      The Dreambound Executioner makes three Vorpal Greatsword attacks.

  - name: Vorpal Greatsword
    desc: |
      Melee Weapon Attack: +11 to hit, reach 10 ft., one target.
    attack_bonus: 11
    damage:
      - dice: 2d12
        bonus: 6
        type: slashing

  - name: Cleaving Arc
    desc: |
      The Executioner swings its blade in a wide arc. Each creature of its choice within 10 feet must succeed on a DC 17 Dexterity saving throw or take slashing damage and be knocked prone.
    save_dc: 17
    save_ability: Dexterity
    damage:
      - dice: 4d10
        type: slashing

  - name: Dreadful Execution (Recharge 5–6)
    desc: |
      The Executioner makes one Vorpal Greatsword attack. On a hit, the target must succeed on a DC 17 Wisdom saving throw or be frightened of the Executioner until the end of its next turn. If the attack was a critical hit, the target is stunned instead.
    save_dc: 17
    save_ability: Wisdom
    damage:
      - dice: 3d12
        type: slashing
